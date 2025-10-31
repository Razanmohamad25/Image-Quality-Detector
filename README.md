# Image-Quality-Detector
Detect if your image is clear or blurry using Laplacian Variance.

# Overview

This is a lightweight Streamlit app that evaluates the quality of images. It calculates the sharpness value using Laplacian Variance and determines if an image is clear or blurry. Designed for demonstration purposes, this version includes only the app interface, screenshots, and a demo video.

 # Features

1-	Detects whether an image is clear or blurry.

2-	Provides a sharpness score for quantitative analysis.

3-	Interactive web interface using Streamlit.

4-	Supports common image formats: JPG, PNG, JPEG.

# Code Description

The app is built using Python and Streamlit for an interactive interface. The main functionality includes:

Image Upload

Users can upload images in .jpg, .png, or .jpeg format.

Image Processing

The uploaded image is converted to grayscale using OpenCV.

Laplacian Variance is computed to measure the sharpness of the image.

Blur Detection

The sharpness value is compared against a predefined threshold (default 100).

If the value is below the threshold, the image is classified as blurry. Otherwise, it’s clear.

# Result Display

Shows the uploaded image alongside the sharpness score.

Displays a clear message: “Image is clear” or “Image is blurry.”

Provides a tip about interpreting the sharpness value.

# Libraries Used

OpenCV (cv2) – image processing and Laplacian calculation.

NumPy – handling image arrays.

PIL (Pillow) – opening and converting images.

Streamlit – building the interactive web interface.


# How It Works

1-	Upload an image via the app.

2-	The app converts the image to grayscale.

3-	Computes the Laplacian Variance to measure sharpness.

4-	Compares the sharpness value against a threshold (default 100).

5-	Displays the result as either clear or blurry along with the score.
