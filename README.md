# Signature-Verifier

This project aims at training a Convolutional Neural Network to classify whether the image of a given signature is genuine or forgery.

## VGG - 16 Architecture

The VGG - 16 model is a simple architecture model, since it's not using much hyper - parameters. It always uses 3 x 3 filters with stride of 1 in convolution layer and uses SAME padding in pooling layers 2 x 2 with stride 2.

![VGG16-architecture.png](VGG16-architecture.png)

Here is the image representing the actual architecture of VGG - 16, as published in the research paper.
Input - Image _[size : 224 x 224 x 3 pixels]_
Output - Flattened image containing N number of pixels _[size : 1 x 1 x N pixels]_

where N is the number of output classes.

## Dataset 

The dataset used in this project is NFI - offline dataset that was used in ICDAR 2009 Signature Verification Competition. The labelling of the images was done in the image file name.

## Content of the Repository

- **Signature** - Contains the Dataset.
- **LICENSE** - Contains license document.
- **README.md** - Contains documenttation of the repository.
- **Submission.ipynb** - Program for Signature Verification.
