# VasculatureVision Project

Welcome to the VasculatureVision project repository! This repository contains code files for our microvasculature segmentation project, aimed at automating the analysis of microvascular structures in histology images from healthy human kidney tissue slides.

## Project Overview

The goal of VasculatureVision is to create a robust and accurate model for segmenting microvascular structures, including capillaries, arterioles, and venules, in 2D PAS-stained histology images. By automating this process, we aim to enhance researchers' understanding of how blood vessels are arranged in human tissues, contributing to the development of a Vascular Common Coordinate Framework (VCCF) and a Human Reference Atlas (HRA).

## Repository Structure

- `k-fold-cv-coco-dataset-generator.ipynb.ipynb`: This notebook guides you through the process of generating the training and validation datasets. It ensures that the data is well-preprocessed and ready for training.
- `Main_model_training.ipynb`: In this notebook, we provide the code for training the microvasculature segmentation model. We leverage various architectures and backbones, ultimately selecting the ResNet-152 backbone for its exceptional performance.
- `Final_Inference_code.ipynb`: Once the model is trained, this notebook demonstrates how to perform inference on new images for microvasculature segmentation.

## Getting Started

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/arpita-kargaonkar/Vasculature-Vision
   ```

2. Follow the instructions in `k-fold-cv-coco-dataset-generator.ipynb.ipynb` to generate your training and validation datasets.

3. Use the code in `Main_model_training.ipynb` to train the microvasculature segmentation model. Feel free to experiment with different architectures and backbones.

4. Once trained, refer to `Final_Inference_code.ipynb` for guidance on using the model for segmenting microvascular structures in new images.

