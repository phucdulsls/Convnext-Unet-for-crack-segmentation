# Crack Segmentation using ConvNeXtV2 + U-Net

## Overview
Semantic segmentation of pavement cracks on the Crack500 dataset.

## Model
- ConvNeXtV2 Base Encoder
- Residual U-Net Decoder

## Dataset
Crack500

## Results

| Model | Dice |
|---------|---------|
| DeepLabV3 | 0.82 |
| U-Net | 0.85 |
| ConvNeXtV2 + Residual U-Net | 0.89 |

## Example Predictions
[ảnh]

## How to Run

python train.py
python predict.py
