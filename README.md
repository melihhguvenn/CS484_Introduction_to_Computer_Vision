# CS484_Introduction_to_Computer_Vision
CS484 - Introduction to Computer Vision - Bilkent University

Homework 1

Overview

This project is for Homework 1 of the CS484/555 course, implementing foundational image processing techniques:

Morphological Operations (Erosion and Dilation)
Histogram-based Image Enhancement
Otsu Thresholding
2D Convolution in the Spatial and Frequency Domain
Each part is implemented in a Jupyter Notebook, demonstrating the application of these techniques on sample images.

Table of Contents
Project Structure
Requirements
Usage
1. Morphological Operations
2. Histogram-based Image Enhancement
3. Otsu Thresholding
4. 2D Convolution in Spatial and Frequency Domain

Requirements
This project requires Python 3 and the following packages:

numpy
matplotlib
scipy
Pillow

1. Morphological Operations
This section includes functions for erosion and dilation using custom structuring elements. The goal is to isolate shapes (e.g., circles) in binary images by applying a sequence of morphological operations.

2. Histogram-based Image Enhancement
This section implements

Histogram Calculation: Computes the histogram of a grayscale image.
Contrast Stretching: Enhances image contrast by stretching pixel intensity values.

3. Otsu Thresholding
Otsu’s method automatically determines a threshold for separating foreground and background in a grayscale image. This minimizes within-class variance and maximizes between-class variance for optimal thresholding.

4. 2D Convolution in Spatial and Frequency Domain
This section demonstrates:

2D Convolution in the Spatial Domain: Using custom filters (e.g., Sobel and Prewitt) to detect edges.
2D Convolution in the Frequency Domain: Using the Convolution Theorem to apply filters in the frequency domain.
Results
The notebook includes output cells showing results for each part:

Morphological Operations: Processed binary images with isolated shapes.
Histogram-based Enhancement: Enhanced images with computed histograms.
Otsu Thresholding: Thresholded images with calculated optimal thresholds.
2D Convolution: Edge-detected images using Sobel and Prewitt filters.
References
Gonzalez, R. C., & Woods, R. E. (2002). Digital Image Processing
Otsu’s Method - Wikipedia
This README is customized for an IPython Notebook workflow, guiding users on setup, usage, and interpretation of results. Let me know if you’d like further adjustments!
