#Image-Quality-Detector
Detect if your image is clear or blurry using Laplacian Variance.

#Overview

This is a lightweight Streamlit app that evaluates the quality of images. It calculates the sharpness value using Laplacian Variance and determines if an image is clear or blurry. Designed for demonstration purposes, this version includes only the app interface, screenshots, and a demo video.

 #Features

1-	Detects whether an image is clear or blurry.

2-	Provides a sharpness score for quantitative analysis.

3-	Interactive web interface using Streamlit.

4-	Supports common image formats: JPG, PNG, JPEG.

#How It Works

1-	Upload an image via the app.

2-	The app converts the image to grayscale.

3-	Computes the Laplacian Variance to measure sharpness.

4-	Compares the sharpness value against a threshold (default 100).

5-	Displays the result as either clear or blurry along with the score.
