
# KITTI 3D Object Detection using FPN + ResNet

This project implements a 3D object detection pipeline using Feature Pyramid Networks (FPN) and a ResNet backbone on the KITTI dataset. The goal is to enhance perception in autonomous driving systems through improved feature representation.

---

## 📌 Objective

- To perform accurate 3D object detection from LiDAR and/or camera inputs.
- Utilize a combination of FPN and ResNet to capture multi-scale spatial features for better bounding box regression and classification.

---

## 🧠 Core Concepts

- **KITTI Dataset**: Benchmark dataset for 3D object detection including camera images, LiDAR scans, and calibration data.
- **Feature Pyramid Network (FPN)**: Multi-scale feature extractor to detect objects at different scales.
- **ResNet Backbone**: Deep residual network for extracting hierarchical image features.
- **3D Bounding Box Regression**: Predict 3D bounding boxes for objects using anchor-based or anchor-free strategies.

---

## 🧰 Requirements

Install dependencies before running the notebook:

```bash
pip install numpy matplotlib opencv-python torch torchvision tqdm
```

Make sure the KITTI dataset is downloaded and properly organized.

---

## 📁 Project Structure

```
Root/
├── KITTI_3D_DetectionUsing FPN+Resenet.ipynb
├── kitti/                     # KITTI dataset folder
│   ├── training/
│   └── testing/
├── models/                    # Custom model definitions (FPN + ResNet)
├── utils/                     # Helper functions for data loading, visualization, metrics
└── outputs/                   # Prediction results and saved models
```

---

## 🚀 How to Run

1. Place the KITTI dataset in the appropriate directory (`kitti/`).
2. Open the notebook:
```bash
jupyter notebook KITTI_3D_DetectionUsing FPN+Resenet.ipynb
```
3. Run all cells step-by-step to:
   - Load and visualize the data
   - Train the 3D detection model
   - Evaluate the results using KITTI metrics

---

## 📊 Results

- Accuracy metrics include 3D IoU, precision-recall, and AP for classes like cars, pedestrians, and cyclists.
- Visualizations show 3D bounding boxes overlaid on LiDAR point clouds and camera images.

---
## 📹 Demonstration
![Demo Video](demo.gif)
## 📄 License

This project is intended for academic and research use only. For commercial use, please contact the author.

---

## 👤 Author

Prithvi Singh Dangas  
May 2025
