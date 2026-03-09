# 🏛️ AI-Driven Archaeological Site Mapping

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Deep Learning](https://img.shields.io/badge/DeepLearning-YOLO%20%7C%20CV-brightgreen)
![Framework](https://img.shields.io/badge/Framework-PyTorch-red)
![Notebook](https://img.shields.io/badge/Environment-Jupyter-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Repo Size](https://img.shields.io/github/repo-size/ShubhamS2005/AIDriven-Archaeological-Site-Mapping)
![Stars](https://img.shields.io/github/stars/ShubhamS2005/AIDriven-Archaeological-Site-Mapping?style=social)

---

# 📖 Overview

**AI-Driven Archaeological Site Mapping** is a research-oriented computer vision project that explores how **deep learning and environmental analysis** can assist in identifying potential archaeological sites.

The system analyzes **vegetation patterns and soil characteristics** from images using AI models to detect anomalies that may indicate **buried structures, ancient settlements, or historical land disturbances**.

The project integrates:

- 🌱 Vegetation Segmentation
- 🪨 Soil Pattern Detection
- 📊 Visual Model Analysis
- 🧠 Explainable AI using Grad-CAM

---

# 🎯 Motivation

Archaeologists often rely on environmental signals such as:

- Abnormal vegetation growth
- Soil discoloration
- Surface texture changes
- Disturbed land patterns

These indicators can reveal hidden structures underground.

This project investigates how **AI models can automatically detect these signals**, helping archaeologists narrow down potential excavation locations.

---

# 🧠 Model Architecture

The deep learning system is built around a **YOLO-based object detection and segmentation pipeline**.

```
Input Image
     │
     ▼
Image Preprocessing
(resizing, normalization)
     │
     ▼
Deep Learning Model
(YOLO Segmentation / Detection)
     │
     ▼
Feature Extraction
     │
     ▼
Prediction Layer
     │
     ▼
Output
 ├── Vegetation Segmentation
 ├── Soil Classification
 └── Bounding Box Detection
```

---

# ⚙️ Project Pipeline

The complete workflow of the system:

```
Satellite / Ground Images
            │
            ▼
     Data Collection
            │
            ▼
     Data Annotation
            │
            ▼
      Model Training
 (Vegetation + Soil Models)
            │
            ▼
      Model Evaluation
   (F1 Curves & Metrics)
            │
            ▼
     Prediction & Testing
            │
            ▼
 Visualization & Explainability
   ├─ Bounding Box Detection
   ├─ Grad-CAM Heatmaps
   └─ Performance Curves
            │
            ▼
 Archaeological Pattern Analysis
```

---

# 📂 Repository Structure

```
AIDriven-Archaeological-Site-Mapping
│
├── ArchilogicalMapping/
│
├── SoilDetection/
│   ├── SoilDetection.ipynb
│   ├── SOIL.md
│   ├── bbox_visualization.png
│   ├── distribution.png
│   ├── gad_cam.png
│   ├── class_labels.json
│   └── test_soil.jpg
│
├── UI-Demo/
│
├── VegetationSegmentation.ipynb
├── VEGETATION.md
├── best.pt
├── data.yaml
├── results.csv
├── veg_test.jpg
│
├── BoxF1_curve.png
├── MaskF1_curve.png
│
├── AgroSensi-AI-2.pptx
└── README.md
```

---

# 🌱 Vegetation Segmentation

Vegetation anomalies can indicate underground structures.

This module trains a deep learning segmentation model to identify vegetation patterns.

### Files

```
VegetationSegmentation.ipynb
VEGETATION.md
best.pt
data.yaml
```

### Outputs

- Vegetation masks
- Bounding box F1 score curve
- Mask segmentation accuracy

Example evaluation plots:

```
BoxF1_curve.png
MaskF1_curve.png
```

---

# 🪨 Soil Detection

Soil composition differences often reveal hidden archaeological features.

The soil detection module performs:

- Soil classification
- Bounding box detection
- Model explainability

### Files

```
SoilDetection.ipynb
SOIL.md
class_labels.json
```

### Visual Outputs

- Dataset distribution plot
- Bounding box visualization
- Grad-CAM interpretability heatmap

```
distribution.png
bbox_visualization.png
gad_cam.png
```

Grad-CAM highlights which image regions influenced model predictions.

---

# 💻 UI Demonstration

The `UI-Demo` directory shows how the AI models could be integrated into a visual interface for archaeologists or researchers.

This allows easier interaction with prediction outputs and visualizations.

---

# 📊 Results

The trained models produce:

- Vegetation segmentation maps
- Soil classification predictions
- Bounding box detections
- Performance metrics
- Grad-CAM explanation maps

Results are saved in:

```
results.csv
```

---

# 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/ShubhamS2005/AIDriven-Archaeological-Site-Mapping.git
```

### Move Into Directory

```bash
cd AIDriven-Archaeological-Site-Mapping
```

### Run Notebooks

Open and run:

```
VegetationSegmentation.ipynb
SoilDetection/SoilDetection.ipynb
```

Execute cells sequentially for training and predictions.

---

# 🔬 Applications

This system can support:

- Archaeological site prediction
- Environmental anomaly detection
- Remote sensing analysis
- Cultural heritage preservation
- AI-assisted archaeological surveys

---

# 🔮 Future Improvements

Potential future extensions:

- Satellite imagery integration
- Multi-spectral remote sensing analysis
- GIS mapping integration
- Web dashboard for visualization
- Real-time site prediction system

---


## Demo Link
https://archilogicalmappingui-ghgvrpkd29qhwrgmcerkyo.streamlit.app/

## Demo use 
Admin, pass 1234


## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

Made with ❤️ by Shubham Srivastava (shubhamsrivastava12568@gmail.com)

⭐ If you find this project useful, consider giving it a star on GitHub!

---




