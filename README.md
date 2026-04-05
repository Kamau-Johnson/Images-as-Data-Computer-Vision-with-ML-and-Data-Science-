# Deep Learning for Computer Vision: Image As Data

<p float="left"> 
  <img src="https://pytorch.org/assets/images/pytorch-logo.png" width="30%" /> 
  <img src="https://pillow.readthedocs.io/en/stable/_static/pillow-logo-dark-text-big.png" width="30%" /> 
  <img src="https://matplotlib.org/stable/_static/logo_light.svg" width="30%" /> 
</p>

### Introduction
This project explores the fundamental representation of images as numerical data using **PyTorch** and **PIL (Pillow)**. The analysis focuses on how computer vision models interpret images through tensors, color channels, and spatial dimensions. 

In this lab, I performed the following:
* **Tensor Manipulation**: Created and sliced tensors from nested lists and images to understand data structures.
* **Hardware Management**: Configured tensors to run on specific devices like **CPU** or **GPU (CUDA/MPS)** for performance optimization.
* **Exploratory Data Analysis**: Analyzed class distributions for a multi-class training dataset containing 8 distinct categories.
* **Image Processing**: Loaded and inspected images of different modes, such as Grayscale ("L") and RGB, along with varied dimensions.
* **Channel Visualization**: Extracted and plotted individual color channels (Red, Green, Blue) to observe pixel intensity distributions.
* **Statistical Analysis**: Calculated channel-wise mean, minimum, and maximum values to prepare for model normalization.

### Import Libraries
```python
import os
import sys
import matplotlib.pyplot as plt
import pandas as pd
import PIL
import torch
import torchvision
from PIL import Image
from torchvision import transforms
```

### Conclusion
The exploration of image data demonstrates that computer vision is built upon high-dimensional matrix manipulation. By converting images to tensors, I observed that grayscale images utilize a single channel (Mode: L) while color images operate in a 3-channel (Mode: RGB) space. The project highlights that image dimensions are organized as (C x H x W)—Channel, Height, and Width. Because raw images vary in size and mode, standardization is a critical prerequisite for training deep learning models.

### Licensing and Usage Guidelines
This project is part of the AI Lab: Deep Learning for Computer Vision at WorldQuant University.

### Usage Guidelines
This file is licensed under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International.

You can:

✓ Download this file

✓ Post this file in public repositories

You must always:

✓ Give credit to WorldQuant University for the creation of this file

✓ Provide a link to the license

You cannot:

✗ Create derivatives or adaptations of this file

✗ Use this file for commercial purposes

#### Note: Failure to follow these guidelines is a violation of your terms of service and could lead to your expulsion from WorldQuant University and the revocation of your certificate.

#### Connect with WQU
#WorldQuantUniversity #WQU #DataScience #MachineLearning #DeepLearning #ComputerVision #Python #PyTorch

Website: https://www.wqu.edu/
