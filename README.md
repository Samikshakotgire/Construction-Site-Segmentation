# Construction Site Instance Segmentation Pipeline 🏗️

## Overview
This project is an end-to-end **Instance Segmentation** pipeline designed for automated monitoring of construction sites. It utilizes **YOLOv8-Seg** to accurately isolate and identify construction workers at the pixel level. 

This pipeline demonstrates a practical application of Computer Vision in **construction technology**, enabling real-time safety compliance and project progress tracking.

## 🚀 Visual Results
![Result Image](segmentation_result.png)

## 🛠️ Tech Stack
* **Framework:** PyTorch
* **Model:** YOLOv8-Seg (Ultralytics)
* **Computer Vision:** OpenCV, Image Segmentation
* **Data Processing:** Roboflow, Python, Kaggle GPU

## 🧠 Model Training & Pipeline
1. **Data Ingestion:** Processed a dataset of construction site imagery, utilizing polygon annotations for instance segmentation.
2. **Model Architecture:** Fine-tuned a pre-trained `yolov8n-seg` model, optimizing for fast, real-world deployment scenarios.
3. **Inference:** The model successfully outputs precise pixel-level masks and bounding boxes, demonstrating robustness against complex construction backgrounds.
