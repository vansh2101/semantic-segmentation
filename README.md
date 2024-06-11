
# Semantic Segmentation

This project focuses on advanced image segmentation using deep learning models. It explores and implements various architectures such as U-Net and SegNet, and includes modifications to improve performance by integrating different layers into the models.


## Table of Contents

* [Introduction](#introduction)
* [Models Implemented](#models-implemented)
* [Modifications and Enhancements](#modifications-and-enhancements)
* [Installation](#installations)
## Introduction

Image segmentation is a crucial task in computer vision with applications in medical imaging, autonomous driving, and more. This project aims to achieve high accuracy in segmenting complex images with multiple classes by leveraging state-of-the-art deep learning models.
## Models Implemented

* **U-Net:** Known for its simplicity and effectiveness in biomedical image segmentation.

* **SegNet:** Features an encoder-decoder architecture with pooling indices, retaining spatial information.

## Modifications and Enhancements

To improve segmentation accuracy, we modified the U-Net architecture by incorporating layers from SegNet and PSPNet. These modifications leveraged the strengths of each model to enhance performance:

* **Dilated Convolution Layers:** Used dilated convolution layers from PSPNet in U-Net's encoder to increase the receptive field of neurons and gather more global information.

* **Layer Structure:** Adopted the layer structure of SegNet within the U-Net architecture to effectively utilize pooling indices and retain spatial information.

## Installation

To set up this project, clone the repository:

```bash
git clone https://github.com/vansh2101/semantic-segmentation.git
cd semantic-segmentation
```
    
