# Neural Style Transfer

This project implements Neural Style Transfer using a Convolutional Neural Network (CNN) based on the VGG-19 architecture. It is used here to create visually appealing images by combining the content of one image with the style of another.

## Model and Implementation

The VGG-19 model, consisting of 16 convolutional and 5 pooling layers, provides the feature space for our style transfer. The fully connected layers of the VGG-19 are not utilized in this process.

## Image Synthesis

To generate a new image that combines the content of a photograph with the style of a painting, we minimize a loss function that balances the content loss from one layer and the style loss from multiple layers. The weighting factors for content and style can be adjusted to achieve the desired artistic effect.

