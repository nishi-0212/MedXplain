# 🧬 Explainable Medical Imaging System (EMIS)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Deep Learning](https://img.shields.io/badge/DL-TensorFlow-orange)
![Computer Vision](https://img.shields.io/badge/CV-Medical%20Imaging-green)

![XAI](https://img.shields.io/badge/XAI-GradCAM%2B%2B-blueviolet)
![XAI](https://img.shields.io/badge/XAI-ScoreCAM-teal)
![XAI](https://img.shields.io/badge/XAI-Saliency%20Maps-purple)
![XAI](https://img.shields.io/badge/XAI-SmoothGrad-9cf)
![XAI](https://img.shields.io/badge/XAI-Occlusion%20Sensitivity-grey)

![CNN](https://img.shields.io/badge/Model-VGG16%20%7C%20ResNet50%20%7C%20EfficientNet-red)


**MedXplain** is an ML-based project that detects **Alzheimer’s Disease, Glaucoma, and Pneumonia** from medical images and explains model predictions using **XAI techniques** like Grad-CAM++ and Score-CAM.

---

## 📌 Overview
This study presents a unified deep learning framework for cross-domain medical image classification across three diseases:

* Alzheimer’s Disease (MRI)
* Glaucoma (Fundus Imaging)
* Pneumonia (Chest X-rays)

The system integrates multiple Explainable AI (XAI) techniques to interpret model predictions and ensure clinical relevance.

## ✨ Features

* Disease Detection using **VGG16**, **EfficientNet** and **ResNet50** CNN models.
* **Explainable AI (XAI):** Visual explanations using **Grad-CAM++**, **Score-CAM**, **Saliency Maps**, **SmoothGrad** and **Occlusion Detection**.
* Supports **three diseases** trained and evaluated separately.
* Clinically interpretable heatmaps for model validation

---

## 🧠 Tech Stack

* **ML Framework:** TensorFlow, Keras
* **Explainability:** Grad-CAM++, Score-CAM
* **Data Analysis:** NumPy, Pandas, Matplotlib, Seaborn
* **Dataset Sources:** Kaggle (Pneumonia), ADNI (Alzheimer’s), DRISHTI-GS (Glaucoma)

---
## 📊 Datasets Used

This study uses publicly available datasets:

* Pneumonia (Chest X-ray): https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
* Glaucoma (Fundus Images): https://www.kaggle.com/datasets/sshikamaru/glaucoma-detection
* Alzheimer's disease (MRI): https://www.kaggle.com/datasets/lukechugh/best-alzheimer-mri-dataset-99-accuracy

## ⚙️ How It Works

1. Input a medical image (MRI, X-ray, or retinal scan).
2. Model predicts the disease class.
3. XAI module highlights regions influencing the prediction.
4. Output includes **disease probability + heatmap explanation**.

---

## 💻 Run Locally

```bash
git clone https://github.com/yourusername/MedXplain.git
cd MedXplain
pip install -r requirements.txt
python main.py
```

---

*Illuminating the Black Box of Medical AI*
