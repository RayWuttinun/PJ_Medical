# PJ_Medical — Medical Image Classification

A deep learning project for **medical image classification**, developed as an end-to-end training and evaluation pipeline using **PyTorch**.

The project focuses on comparing multiple CNN architectures for multi-class medical image classification and analyzing their training performance.

## Project Overview

This project explores how different convolutional neural network architectures perform on a medical image classification task.

### Key Highlights

* **188K+ training samples**
* **72 image classes**
* End-to-end training and validation pipeline
* Comparison of multiple CNN architectures
* Training and validation performance analysis
* Implemented with **PyTorch**

## Models

Three CNN architectures were trained and evaluated:

| Model                 | Purpose                                   |
| --------------------- | ----------------------------------------- |
| **ResNet50**          | Baseline deep CNN architecture            |
| **EfficientNet-B3**   | Evaluate efficiency-oriented architecture |
| **MobileNetV3-Large** | Evaluate a lightweight CNN architecture   |

## Pipeline

```text
Medical Image Dataset
        │
        ▼
Data Preparation
        │
        ├── Data Organization
        ├── Preprocessing
        └── Augmentation
        │
        ▼
Train / Validation
        │
        ├── ResNet50
        ├── EfficientNet-B3
        └── MobileNetV3-Large
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

## Dataset

The dataset contains **188K+ samples across 72 classes**.

The training pipeline includes image preprocessing and augmentation before the images are passed to the classification models.

> Dataset files are not included in this repository.

## Results

Training outputs for each architecture are provided in the repository:

* `outputs_resnet50/`
* `outputs_efficientnet_b3/`
* `outputs_mobilenet_v3/`

Training comparisons and dataset distributions are also included:

* `training_comparison.png`
* `training_data_distribution.png`

These outputs are used to compare model training behavior and performance across architectures.

## Project Structure

```text
PJ_Medical/
│
├── Data_text/
│
├── outputs_efficientnet_b3/
├── outputs_mobilenet_v3/
├── outputs_resnet50/
│
├── main.ipynb
├── pyproject.toml
│
├── training_comparison.png
└── training_data_distribution.png
```

## Tech Stack

* Python
* PyTorch
* CNN / Deep Learning
* ResNet50
* EfficientNet-B3
* MobileNetV3-Large
* Jupyter Notebook

## What I Worked On

* Built the training and validation pipeline for medical image classification.
* Prepared and processed a large-scale image dataset.
* Applied image augmentation during training.
* Trained and compared three CNN architectures.
* Analyzed training behavior and model performance.
* Investigated differences between deeper, efficiency-oriented, and lightweight CNN architectures.

## Purpose

This project was developed to gain practical experience in **computer vision, deep learning model development, dataset preparation, and experimental model comparison**.

