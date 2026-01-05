# Vegetation Segmentation Project

## Project Overview
This project focuses on **Vegetation Segmentation** using the **YOLOv8 Segmentation model**. The goal is to accurately detect and segment vegetation areas in images for applications such as agriculture monitoring, environmental analysis, and land-use assessment.

---

## Features
- **Object Detection & Segmentation** using YOLOv8.
- Supports **training, validation, and testing** on custom datasets.
- **Real-time inference** for vegetation detection.
- Exportable **segmentation masks** and bounding boxes.
- Modular structure for easy integration into other applications.

---

## Dataset
The project uses a structured dataset organized as follows:

---


> **Note:** Images and annotations must be in YOLO-compatible format. Use Roboflow or custom scripts to convert data if necessary.

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/vegetation-segmentation.git
cd vegetation-segmentation
```

2.  Create a virtual environment and activate it:
```bash
conda create -n vegseg python=3.10 -y
conda activate vegseg

```

3. Install dependencies:
```bash
pip install -r requirements.txt


```

4. Install YOLOv8 (Ultralytics):
```bash
pip install ultralytics
```

## Dependencies
1. Python 3.10+
2. Ultralytics YOLOv8
3. numpy
4. pandas
5. matplotlib
6. opencv-python
7. tqdm


