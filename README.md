# Cross-Age Facial Recognition of Public Personalities (8 Classes)

This repository contains the implementation and results for a cross-age facial recognition study using multiple CNN architectures.  
The experiments focus on recognising 8 well-known personalities where:

- **Training set:** 2,400 images (300 per class), collected from images **before 2020**
- **Test set:** 240 images (30 per class), collected from **2024–2025**
- **Task:** Semi-supervised facial recognition with a pronounced **time gap** between training and test images  
- **Goal:** Evaluate how different CNN architectures handle age, style, and appearance changes over time

All model implementations are provided as Jupyter notebooks (`.ipynb`), with corresponding performance metrics in `.csv` format and a consolidated analysis file used in the report.

---

## Architectures Covered

The following CNN architectures are implemented and evaluated through transfer learning:

- **VGG-19**
- **ResNet-50**
- **EfficientNet-B0**
- **MobileNetV2**
- **MobileNetV3-Large (1.0)**
- **ResNeXt-50 (32x4d)**
- **ConvNeXt-Small**

Each notebook:

- Loads the prepared dataset of 8 personalities
- Applies the chosen CNN model (with appropriate classifier head)
- Trains/evaluates on the defined train–test split
- Exports key metrics (accuracy and related performance indicators)

---

## The Files for the Respective Experiments (.ipynb for codes, .csv for performance metric results and analysis)

```text
.
├── VGG_19.ipynb
├── VGG-19_PM.csv_PM.csv
│
├── ResNet_50.ipynb
├── ResNet50_PM.csv
│
├── EfN_B0.ipynb
├── Efn-B0_PM.csv
│
├── MobileNetV2.ipynb
├── MobileNetV2_PM.csv
│
├── MobileNetV3_Large(1.0).ipynb
├── MNV3L1_PM.csv
│
├── ResNeXt_50_(32x4d).ipynb
├── ResNeXt-50(32x4d)_PM.csv
│
├── ConvNeXt_Small.ipynb
├── ConvNeXt(Small)_PM.csv
│
├── Analysis of Results.xlsx 
│ (This Analysis contains the graphs, tables, used in the report)
└── README.md
