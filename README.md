# Emotion-Detection
![images](https://user-images.githubusercontent.com/85367784/145420078-3315bdf1-2082-48c6-97ab-de6c5506ffa6.jpg) 
![48102098-ab737b80-e1e6-11e8-8541-517de2be0064](https://user-images.githubusercontent.com/85367784/145424952-d353bc4c-e638-431c-9cb9-e745b40c5cad.png)
Emotion recognition is the process of identifying human emotion.

# DATASET
Dataset used is FER.csv
Facial Emotion Recognition on FER2013 Dataset Using a Convolutional Neural Network.

# Prerequisites
Install these prerequisites before proceeding-
 pip3 install tensorflow
 pip3 install keras
 pip3 install numpy
 pip3 install sklearn
 pip3 install pandas
 pip3 install opencv-python
 
 # CascadeClassifier
 haarcascade_frontalface_default.xml
 
 # Model Summary
 Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d (Conv2D)              (None, 44, 44, 32)        832       
_________________________________________________________________
max_pooling2d (MaxPooling2D) (None, 22, 22, 32)        0         
_________________________________________________________________
conv2d_1 (Conv2D)            (None, 18, 18, 64)        51264     
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 9, 9, 64)          0         
_________________________________________________________________
flatten (Flatten)            (None, 5184)              0         
_________________________________________________________________
dense (Dense)                (None, 100)               518500    
_________________________________________________________________
dense_1 (Dense)              (None, 10)                1010      
=================================================================
Total params: 571,606
Trainable params: 571,606
Non-trainable params: 0
