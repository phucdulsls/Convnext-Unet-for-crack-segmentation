# Crack Segmentation using ConvNeXtV2 + Residual U-Net

Semantic segmentation of pavement cracks on the Crack500 dataset using a ConvNeXtV2 encoder and a Residual U-Net decoder.

---

## Overview

This project implements a deep learning pipeline for pavement crack segmentation. The proposed model combines the feature extraction capability of ConvNeXtV2 with the precise localization ability o[...]

For a detailed explanation of the methodology, experiments, implementation, and evaluation, please refer to the project report in the **docs/** folder.

📄 **Full Project Report:** `docs/Final_Report.pdf`

---

## Model Architecture

- ConvNeXtV2 Base Encoder
- Residual U-Net Decoder
- Binary Semantic Segmentation

---

## Dataset

- Crack500
- Image Size: 384 × 384
- Binary crack masks

---

## Results

| Model | Dice Score |
|-------|-----------:|
| DeepLabV3 | 0.82 |
| U-Net | 0.85 |
| ConvNeXtV2 + Residual U-Net | **0.89** |

---

## Demo

<p align="center">
  <img src="assets/demo.gif" width="900">
</p>

---

## Example Predictions

<p align="center">
  <img src="assets/prediction_examples.png" width="900">
</p>

---

## Screenshot

<p align="center">
  <img src="Screenshot 2026-07-07 222433.png" width="900">
</p>

---

## Project Structure

```text
.
├── assets/
├── docs/
│   └── Final_Report.pdf
├── models/
├── train.py
├── predict.py
└── README.md

```
