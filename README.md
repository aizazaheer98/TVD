# TVD
# "DOWNLOAD TVD.rar FILE TO VIEW COMPLETE CODE"
TVD is abbreviation for Traffic Violation Detector. TVD has been built in "Google Colaboratory" in Python language. This project aims at finding two types of traffic violations that are:

Driving on the Footpath.
Driving in the Wrong Lane.
TVD uses the pre-trained model "Deeplab_resnet101_ade" provided by PyTorch. This model has been trained on "ADE20K" dataset which classifies 150 different classes. Image segmentation and image processing techniques have been used to detect the aforementioned first violation.

Optical flow technique in computer vision has been implemented to characterize the motion of objects in the input video streams, thus helping to detect the second type of violation.
