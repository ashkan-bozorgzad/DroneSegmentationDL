# Drone Image Segmentation using Deep Learning

## Overview
This project focuses on segmenting drone-captured images into multiple classes using advanced deep learning techniques. The goal is to develop accurate segmentation models that can process drone imagery efficiently for various applications, such as urban planning and environmental monitoring.

## Features
- Data preprocessing for drone images and masks, including patch extraction.
- U-Net and ResNet50-based segmentation architectures.
- Dynamic learning rate adjustments during training.
- Real-time prediction visualization during training.
- Comprehensive evaluation and visualization of model performance.

## Dataset
The dataset for this project is sourced from [TU Graz](https://www.tugraz.at/index.php?id=22387). It consists of drone images and their corresponding segmentation masks. Preprocessing steps include converting RGB masks to integer-labeled masks suitable for segmentation models.

## Model Architectures
### U-Net
A classic image segmentation model with an encoder-decoder structure and skip connections for precise segmentation.

### Improved U-Net with ResNet50 Backbone
An enhanced architecture that uses ResNet50 as a feature extractor, combined with a custom decoder for high-resolution segmentation outputs.

## Training
The training pipeline leverages dynamic learning rate adjustment using `ReduceLROnPlateau`, combined with data augmentation techniques. Models are evaluated on validation datasets to monitor overfitting and optimize generalization.

## Author
This project was developed by **Ashkan Bozorgzad**.

## Acknowledgments
- The dataset is provided by [TU Graz](https://www.tugraz.at/index.php?id=22387).


## License
This project is open-source and available under the MIT License.
