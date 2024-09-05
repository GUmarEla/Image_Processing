# Image_Processing

# Librarie needed for all this project
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import cv2

# All the algorithms in this project:

1 - Image Enhancement
histogram_equalization(image)
contrast_image(image)
retinex(image)

2 - Image Filtering
gaussian_smoothing(image, kenel_size, sigma)
linear_spatial_filter(image, kernel)
frequency_ideal_low_pass(image, D0)
frequency_ideal_high_pass(image, D0)
frequency_ideal_band_pass(image, D1, D2)
frequency_ideal_band_stop(image, D1, D2)
median_filter(image)
bilateral_filtering(image, kernel_dimension, SigmaS, SigmaR)
homomorphic_filter(image, sigma, alpha, beta)

3 - morphological Operations
erosion(image, kernel_dimension)
dilation(image, kernel_dimension)
opening(image, kernel_dimension)
closing(image, kernel_dimension)
gradient(image, kernel_dimension)
inverse_gradient(image, kernel_dimension)
top_hat(image, kernel_dimension)
black_hat(image, kernel_dimension)

4 - ColorImage Processing
RGB_to_Gray(image)
RGB_to_HSV(image)
RGB_to_HLS(image)
color_balence(image, type)
gamma_correction(image, gamma)
histogram_equalization_channel(image)

5 - Image Restoration
translation(image, Tx, Ty)
scaling(image, a, b)
rotate(image, theta)
perspective_transformation(image, H)
warping(image, transformation_type, matrix)
