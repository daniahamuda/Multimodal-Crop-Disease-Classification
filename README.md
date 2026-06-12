# Multimodal Crop Disease Classification

## Overview

Deep learning framework for crop disease classification using multimodal remote sensing imagery.

The system combines:

- Hyperspectral imagery (125 bands)
- Multispectral imagery (5 bands)
- RGB imagery

through a novel SE-guided multimodal fusion architecture.

## Proposed Model

SEFusionNet

- ConvNeXt-Small Backbone (Hyperspectral Branch)
- EfficientNet-B2 Backbone (MS + RGB Branch)
- Squeeze-and-Excitation Feature Fusion
- Focal Loss
- AdamW Optimizer
- OneCycleLR Scheduler

## Dataset

ICPR 2026 AgVision Competition Dataset

Classes:

- Health
- Rust
- Other

## Training Strategy

- 5-Fold Stratified Cross Validation
- Weighted Random Sampling
- Gradient Clipping
- Early Stopping
- Data Augmentation

## Results

Best Fold Validation Accuracy:

99.17%

## Technologies

- Python
- PyTorch
- timm
- Albumentations
- Scikit-Learn

## Authors

- Owen Alshobaki
- Dania Abu Zidan
- Reem Barakat
- Dana Elyyan

University of Jordan
