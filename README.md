# Transfer-Learning-Car-Recognition
# Motivation
It is difficult to directly train deep learning model on this dataset because the limited number of images. Thus we decide to use transfer learning, a common approch used in deep learning to utilize the pretrained model on [imagenet](http://www.image-net.org/) and fine-tune on our own dataset, i.e. car dataset.

# Dataset
This project is about car classification for [stanford car dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html). The Cars dataset contains 16,185 images of 196 classes of cars. The data is split into 8,144 training images and 8,041 testing images, where each class has been split roughly in a 50-50 split. Classes are typically at the level of Make, Model, Year, e.g. 2012 Tesla Model S or 2012 BMW M3 coupe.



# Procedure
+	Constructed data pipeline by PyTorch to extracted and transformed Stanford car images dataset (1.96GB dataset with 196 classes) 
+	Modified and tuned pre-trained models Google-Net, VGG-16 , Res-Net 50 to fit car dataset using early stopping, weight decay techniques
+	Improved test accuracy of the best model to 85% using cross-validation model selection techniques

# Result and Evaluation
Please Check results in my notebook
