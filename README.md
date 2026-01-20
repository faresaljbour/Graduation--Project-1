# Vision-Based Fall Detection Using YOLO

This repository presents a vision-based fall detection system developed using a YOLO-based object detection framework. The proposed system is designed to automatically detect fall and non-fall events from still images, aiming to enhance safety monitoring in indoor environments such as homes, hospitals, and elderly care facilities.

The project focuses on achieving high detection accuracy while maintaining computational efficiency suitable for real-time applications.

---

## Project Overview

Falls represent a significant risk, particularly for elderly individuals and patients in healthcare environments. This project proposes a computer vision-based solution that utilizes deep learning and object detection techniques to identify fall events from visual data.

The system employs a YOLO-based model capable of detecting human postures and classifying them into fall and non-fall categories using bounding box predictions.

---

## Methodology

The proposed system follows a structured pipeline consisting of the following stages:

1. Dataset preparation and organization
2. Data preprocessing and normalization
3. YOLO-based model training using supervised learning
4. Model evaluation using standard object detection metrics

---

## Dataset Description

The dataset used in this project contains approximately **18,000 labeled images** representing two classes:

- **Fall**
- **No-Fall**

All images are annotated in **YOLO format**, where each annotation file includes class labels and normalized bounding box coordinates.

The dataset is split into three subsets:
- **Training set**
- **Validation set**
- **Testing set**

This split ensures reliable model training and unbiased performance evaluation.

> â ï¸ **Note:**  
> Due to dataset size and usage restrictions, the dataset is **not included** in this repository.  
> Users are expected to provide their own dataset following the same structure and annotation format.

---

## Model Architecture

The system utilizes a YOLO-based object detection model implemented using the **Ultralytics** framework. YOLO was selected due to its ability to perform object detection in a single forward pass, making it well-suited for real-time fall detection applications.

---

## Evaluation Metrics

Model performance is evaluated using standard object detection metrics, including:
- Precision
- Recall
- Mean Average Precision (mAP)

These metrics provide a comprehensive assessment of the modelâs detection accuracy and robustness.

---

## Repository Structure

