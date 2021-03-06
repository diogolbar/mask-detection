# Facial Mask Detection

In this project we implement a [facial mask classifier](https://nbviewer.jupyter.org/github/diogolbar/mask-detection/blob/main/MaskClassifier.ipynb) using a pre-trained convolutional neural network ([MobileNetV2](https://www.tensorflow.org/api_docs/python/tf/keras/applications/MobileNetV2)) as the base model and adding extra layers. With [OpenCV](https://nbviewer.jupyter.org/github/diogolbar/mask-detection/blob/main/FaceMaskRecog.ipynb) we also made possible for this classification to have a visual result as showed bellow:
![](onefacemask.png)

![](maskfinal.png)
where we used a green rectangle to represent a mask detection and a red one when no mask is detected. The code also displays the text "Mask" or "No Mask". We also used the same model for mask detection using a [webcam](mask_recog.py) (yes, this is me): 

![](camtest.gif)

This project is still under development and need to be improved since some faces and masks are not detected.

Data Source: [Kaggle](https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset)
 
