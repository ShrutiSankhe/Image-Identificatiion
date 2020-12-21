# Image-Identification
A system for classifying images using SVM (support vector machine) classification algorithm

The project consists of five essential stages: 
1.	Data Collection 
2.	Data Cleaning 
3.	Feature extraction using wavelet transform 
4.	Training model using SVM 
5.	Visualization and model analysis 


1. The data collection phase innvolves collection of the images. This phase id important for creating a dataset of images for training and testing purposes. 
2. The data cleaning stage involves cleaning the images by getting rid of the ones which do not have distinguishing facial features. OpenCV library is used to detect face and eyes. OpenCV stands for Open-Source Computer Vision. It is a library comprising functions for computer vision. This library emphasizes on functionality of real-time image processing and implementation of the machine learning algorithms. OpenCv has a statistical machine learning library which supports facial and gesture recognition, gesture classification, mobile robotics, object identification and motion sensing. 
3. In the feature extraction, wavelet transform is used to extract meaningful features that can help with image classification. The wavelet transform returns a raw pixel image which is further used for the training the model. 
4. In the training model, an SVM model is created to get the performance on the model of image classification. By using sklearn classification_report to check the performance of the trained models. 
5. Visualization and model analysis evaluates performance of the model. Confusion matrix is used with seaborn visualization to get an understanding of classification errors for each of the classes. 
