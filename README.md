# Biological Histopathological Image Segmentation

## Overview
This project focuses on biological histopathological image segmentation using deep learning models. The primary goal is to enhance and optimize segmentation accuracy using various architectures.

## Models Used
The following models have been implemented for image segmentation:

- **U-Net**: A convolutional network designed for biomedical image segmentation.
- **ResNet**: A residual network that improves the performance of image classification and segmentation tasks.
- **DeepLab**: A model that leverages atrous convolution and fully connected CRFs for precise segmentation.

## Project Structure
The repository is organized as follows:

- **U-Net/**: Contains segmentation results and relevant files for the U-Net model.
- **ResNet/**: Contains segmentation results and relevant files for the ResNet model.
- **DeepLab/**: Contains segmentation results and relevant files for the DeepLab model.
- **Gt/**: Contains ground truth images used for comparison.
- **Img/**: Contains the masks for the images used in the segmentation process.
- **Gt-Test/**: Contains ground truth images for testing.
- **Img-Test/**: Contains maks for the images for testing.
- **target.png**: A base image used for color normalization through the Reinhard method.

## Running the Project
This project is set up to run using Google Colab. Follow these steps:

1. **Open Colab Notebook**: Navigate to the provided Colab notebooks in the repository. You can open them directly in Google Colab by clicking on the link.

2. **Upload Data**: Upload the necessary data files (images and ground truth) to their respective Google Drives. Ensure that the paths in the Colab notebooks are updated to point to these files.

3. **Run Cells**: Execute the cells in the notebook sequentially. The notebooks contain all the code and instructions needed for running the segmentation models and analyzing the results.

4. **Color Normalization**: Use the provided code to apply color normalization to images using `target.png` with the Reinhard method.

## Results
The segmentation results for each model are saved in their respective folders. You can visualize the output and assess the performance using standard metrics.
