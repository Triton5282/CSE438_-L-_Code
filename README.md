# CSE438 – Digital Image Processing  
## Semi-Supervised Image Segmentation Project

This repository contains the complete and consolidated code submission for the **CSE438 (Digital Image Processing)** course project.  
The project explores **supervised and semi-supervised learning techniques** for image segmentation, with a focus on reducing labeled data requirements while maintaining high segmentation performance.

---

## 📌 Project Overview

Image segmentation is a fundamental task in digital image processing and computer vision. However, pixel-level annotation is expensive and time-consuming.  
This project investigates whether **semi-supervised learning (SSL)** methods can achieve performance comparable to fully supervised models by leveraging unlabeled data.

The project includes:
- A **baseline supervised segmentation model**
- **Semi-supervised segmentation approaches**
- A **final consolidated SSL segmentation pipeline**

---

## 📁 Repository Structure

CSE438_-L-_Code/
│
├── Assignment1_Baseline/
├── Assignment2_SSL/
├── FinalProject_SSL/
├──data/
├──results/
├── requirements.txt
└── README.md

---

## 🧠 Implemented Methods

### 1. Supervised Learning
- YOLO-based segmentation model
- Trained using fully labeled data
- Serves as the baseline for comparison

### 2. Semi-Supervised Learning
The following SSL techniques were implemented:
- **FixMatch**
- **MixMatch**
- **Teacher–Student (Self-Training)**

## ⚙️ Hardware and Environment

- **GPU:** NVIDIA Tesla P100 (16 GB VRAM)
- **CPU:** Intel Xeon
- **RAM:** 16–30 GB
- **Language:** Python 3
- **Frameworks:** PyTorch, Ultralytics YOLO
- **Environment:** Jupyter Notebook / Python scripts

## 👥 Contributors

- **Tirtho Das** — East West University, Bangladesh  
- **Faria Tasnim Era** — East West University, Bangladesh  
- **Israt Jahan Orchee** — East West University, Bangladesh

