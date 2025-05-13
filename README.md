# Comparative Analysis of Diverse Architectures for Accurate Blood Cancer Cell Classification
## Papaer link in IEEE- https://ieeexplore.ieee.org/abstract/document/10497341
📄 *Published in:* 2024 International Conference on Computer, Electrical & Communication Engineering (ICCECE)  
📅 *Date:* 2024  
📍 *Pages:* 1–6  
🔗 *Citations:* Cited by 1 (as of 2024)

---

## 🧠 Overview

This repository hosts the official code, experimental setup, and supplementary information for the research:

> **"Comparative Analysis of Diverse Architectures for Accurate Blood Cancer Cell Classification"**  
> *Authors:* Montaser Abdul Quader, G. K. Md. Muttakin, Farhana Yesmin, Syeda Sadia Alam, Md Sadi Ashraf, Vishwanath Akuthota

This work presents a comparative study of multiple deep learning architectures tailored for **blood cancer cell image classification**. With the aim of enhancing diagnostic speed and accuracy, we investigate various CNN-based models and their ability to effectively classify microscopic blood cell images into cancerous or healthy categories.

---

## 🔍 Problem Statement

The classification of cancerous blood cells via microscopy is often labor-intensive and prone to human error. Automating this process can lead to:

- Faster and more consistent diagnostics
- Lower dependency on expert interpretation
- Early-stage detection of leukemia and other hematological malignancies

---

## 🏥 Methodology

We examined and compared multiple deep learning architectures including:

- **Standard CNN**
- **ResNet-50**
- **InceptionV3**
- **EfficientNetB0**
- **DenseNet-121**

### 🧪 Dataset

- Publicly available dataset of **blood smear images**
- Binary classification: **Cancerous vs. Healthy**
- Data preprocessing included resizing, normalization, and augmentation to enhance generalizability

---

## 📊 Results Summary

| Model          | Accuracy | Precision | Recall | F1-Score |
|----------------|----------|-----------|--------|----------|
| CNN (Baseline) | 85%      | 84%       | 83%    | 83.5%    |
| ResNet-50      | 91%      | 90%       | 89%    | 89.5%    |
| InceptionV3    | 90%      | 89%       | 88%    | 88.5%    |
| **EfficientNetB0** | **93%** | **92%**   | **92%**| **92%**  |
| DenseNet-121   | 92%      | 91%       | 91%    | 91%      |

> **Conclusion:** EfficientNetB0 delivered the best performance in terms of accuracy and class balance, making it a promising choice for real-world blood cancer cell classification tasks.

---

## 🗂️ Repository Structure

```bash
├── dataset/                 # Image dataset and metadata
├── preprocessing/           # Data cleaning and augmentation scripts
├── models/                  # Architectures and training scripts
├── results/                 # Evaluation metrics and sample predictions
├── notebooks
