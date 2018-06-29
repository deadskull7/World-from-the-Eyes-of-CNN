# World-from-the-Eyes-of-CNN

### Heatmap superimposed on original image to evaluate where the CNN is focussing the image in order to distinguish it.
#### Following are the 2 Examples for the same -
![activation_map_lady.png](activation_map_lady.png) 
![activation_map_me.png](activation_map_me.png)

## Image through convolutional layer , maxpool layer and an activation layer. 
## The image would even give a twinkling effect on scrolling due to enough noise !!!
![CNN_visuals_1.png](CNN_visuals_1.png)
## Image through Conv layer and activation layer only. Notice the edges of the car in the softmax activated feature map.
![CNN_visuals_2.png](CNN_visuals_2.png)
## Image through Conv layer only. Now a bit closer look at the headlights, tyres , grill which have been focussed in this feature map. Notice the car's number plate , how it got bigger, focussed and clearer than before.
![CNN_visuals_3.png](CNN_visuals_3.png)

**My work includes the study of image transformation in various steps of a convolutional neural network when it passes the Conv2D layer, maxpool layer and an activation layer. And how the CNN percieves it or on which part of the image the CNN is focussing in order to distinguish the image into various classes. I have also studied GRAD-CAMs a bit using VGG16 weights till the last fully connected layer and tried to apply the same on those images. Studied the activated feature maps. You shall study the same using other imagenet models like Resnet , inceptionV3, etc. I have tested the GRAD-CAMs on a photo of mine and a potrait of a lady.**
