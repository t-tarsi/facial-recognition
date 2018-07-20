# Transfer Learning for Facial Recognition

## transfer_learning.ipynb:
Repurposed the convolutional base from InceptionV3 (with pretrained weights from ImageNet), to differentiate between human faces.
Added 2 dense layers on top of the convolutional base and trained the new layers on 38 human faces.

## CroppedYale/ : 
Folder with data as received from Yale Face Database.

## data/ :
Reformatted data to work smoothly with Keras interface.
