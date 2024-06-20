# Brain Tumor Segmentation using UNet architecture
## Overview
This project focuses on the segmentation of brain tumors from MRI images using the UNet architecture, a popular deep learning model for biomedical image segmentation. 
The UNet model is designed to effectively handle the segmentation task with high accuracy by learning from a large dataset of labeled MRI images.

## Features
- **UNet Architecture**: Implemented using PyTorch, known for its encoder-decoder structure which provides precise localization and efficient learning.
- **Data Augmentation**: Utilizes various data augmentation techniques to enhance the generalization capability of the model.
- **Model Evaluation**: Comprehensive evaluation metrics including Dice coefficient and Intersection over Union (IoU) for performance measurement.
- **Visualization**: Tools for visualizing the segmentation results alongside the ground truth for better interpretability.

## Dataset
The data used for training in this project is obtained from [Kaggle](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation). This dataset contains brain MR images together with manual FLAIR abnormality segmentation masks.
The images correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.

### Prerequisites
- Python 3.6+
- Torch 2.x
- NumPy
- OpenCV
- Matplotlib

## Results

<p align="center">
  <img src="https://github.com/aman06012003/Brain-Tumor-Segmentation/assets/84065246/3e2d3fcf-bb56-40b7-85a3-eac329b1a281" alt="Some of the results after training" width="700" />
  <br>
  <em>Some of the results after training</em>
</p>


