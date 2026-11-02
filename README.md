Mask Generation of Microscopic Images

Project Overview

This research-oriented project focuses on generating segmentation masks from microscopic images using image processing and deep learning techniques. The objective is to identify and segment relevant regions in microscopic images to support image-based analysis.

The project explores the combination of Fuzzy C-Means (FCM) clustering and Attention U-Net for microscopic image segmentation, with a focus on improving segmentation accuracy.

Dataset

- Total microscopic images: 212
- Benign images: 99
- Malignant images: 113
- Images are organized into Benign (B) and Malignant (M) categories.

Methodology

1. Image Preprocessing: Microscopic images are resized to 256 × 256 pixels and prepared for segmentation.
2. Fuzzy C-Means Clustering: FCM clustering with four clusters is applied to identify image regions.
3. Mask Generation: Segmentation masks are generated to represent the regions of interest.
4. Attention U-Net: An Attention U-Net architecture is used for deep learning-based segmentation.
5. Model Training: The network learns to generate segmentation masks from the microscopic images.
6. Evaluation: Segmentation performance is assessed using the Dice Similarity Coefficient.

Technologies Used

- Python
- Google Colab
- OpenCV
- NumPy
- TensorFlow / Keras
- Fuzzy C-Means Clustering
- Attention U-Net
- Image Segmentation

Results

The project evaluates segmentation performance separately for benign and malignant image categories.
Dice score 0.93

Project Type

Research-oriented project in Medical Image Processing and Deep Learning.
