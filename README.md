**Day 1: Setting up Environment**

Objective: Prepare Python environment and libraries for Sign Language Recognition System.

Steps Completed:

Installed Python 3.10 in Anaconda (because TensorFlow/Keras/Mediapipe work best with 3.8–3.11).

Created a virtual environment:
'''conda create -n signlang python=3.10
conda activate signlang'''


Installed required libraries:
'''pip install opencv-python tensorflow keras mediapipe numpy matplotlib'''


Verified libraries inside the environment:

'''import cv2
import tensorflow as tf
import keras
import mediapipe as mp
import numpy as np
import matplotlib.pyplot as plt'''
