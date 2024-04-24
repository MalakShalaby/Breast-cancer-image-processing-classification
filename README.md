# Breast Cancer Detection using Image Processing and CNN

This repository contains a project aimed at developing a breast cancer detection system using image processing techniques and convolutional neural networks (CNN).

## Overview

The project involves preprocessing mammogram images (Mias database) to enhance features relevant to cancerous tissue, followed by training a CNN model to classify the images as malignant or benign.

## Preprocessing Pipeline

The preprocessing pipeline includes the following steps:

1. **Conversion to Grayscale**: Convert the input image to grayscale.
2. **Contrast Limited Adaptive Histogram Equalization (CLAHE)**: Enhance contrast using CLAHE.
3. **Median Filtering**: Apply median filtering for noise reduction.
4. **Segmentation**: Perform segmentation using Otsu's thresholding method.
5. **Morphological Operations**: Apply morphological operations for further refinement.
6. **Contour Detection**: Detect contours of the processed image.

## CNN Model

The CNN model architecture consists of several convolutional and pooling layers followed by fully connected layers for classification.

## Histogram Display and Contrast Improvement Index (CII)

This section displays histograms of images before and after preprocessing, along with calculating the Contrast Improvement Index (CII) between different preprocessing methods.

## Usage

To use this project, follow these steps:

1. Clone the repository: `git clone <repo_url>`
2. Install the necessary dependencies (see `requirements.txt`).
3. Run the preprocessing pipeline on your dataset using the provided scripts.
4. Train the CNN model using the preprocessed images.
5. Evaluate the model and make predictions on new data.

## Dependencies

- OpenCV (`cv2`)
- scikit-image (`skimage`)
- pandas
- TensorFlow (`tensorflow`)
- matplotlib

