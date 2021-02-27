# Image-Classifications-w-TensorFlow
  
Beans is a dataset of images of beans taken in the field using smartphone cameras. 
It consists of 3 classes: 2 disease classes and the healthy class. Diseases depicted
include Angular Leaf Spot and Bean Rust. Data was annotated by experts from the National
Crops Resources Research Institute (NaCRRI) in Uganda and collected by the Makerere
AI research lab.

This data has been downloaded from Tensorflow dataset
at: https://www.tensorflow.org/datasets/catalog/beans


Homepage: https://github.com/AI-Lab-Makerere/ibean/

Source code: tfds.image_classification.Beans

Versions:

0.1.0 (default): No release notes.
Download size: Unknown size

Dataset size: 171.63 MiB

Auto-cached (documentation): Yes (test, validation), Only when shuffle_files=False (train)


In this study, I used the following libraries:
import os
import PIL
import numpy as np
import tensorflow as tf
import matplotlib.pyplot as plt
import tensorflow_hub as hub
from tensorflow.keras import layers
from tensorflow.keras import Model
from tqdm import tqdm
from tensorflow.keras.preprocessing.image import ImageDataGenerator
