# Project Name - Gesture Recognition Case Study
To develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command.


## Table of Contents
* [General Information](#general-information)
* [Observations](#Observations)
* [Libraries Used](#libraries-used)


## General Information
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
1. Thumbs up: Increase the volume
2. Thumbs down: Decrease the volume
3. Left swipe: 'Jump' backwards 10 seconds
4. Right swipe: 'Jump' forward 10 seconds
5. Stop: Pause the movie
Each video is a sequence of 30 frames (or images)



## Observations

1. Model has achieved training accuracy of 90% and validation accuracy of 84%
2. The trainable parameters is equal to 1,267,685 which is less as compared to other models
3. Model is made to overfit. Then overfitting is handled by increasing dropout value in model
4. Conv3D model performs better than CNN + GRU model
5. ReduceLROnPlateau callback helps to reduce learning rate if no change in loss is observed
6. Center cropping is not performed because the information is lost at edges and accuracy obtained was less


## Libraries Used
- numpy
- skimage
- imageio
- Keras

## Contact
Created by AparnaBindage - feel free to contact me!