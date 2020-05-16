# TVD

# "DOWNLOAD TVD.rar FILE TO VIEW COMPLETE CODE"

TVD is abbreviation for Traffic Violation Detection. TVD aimes at findinf two types of traffic violations that are:
1) Driving on the Footpath.
2) Driving in the Wrong Lane.

TVD uses the pre-trained model "Deeplab_resnet101_ade" provided by PyTorch. This model has been trained on "ADE20K" dataset which classifies 150 different classes. Image segmentation and image processing techniques have been used to detect the first violation.

Optical flow tehcnique in computer vision has been implemented to characterize the motion of objects in the input video streams, thus helping to detect the second type of violation.
