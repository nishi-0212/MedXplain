# 🩺 MedXplain – Multi-Disease Medical Imaging with XAI

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/ML-TensorFlow-orange)
![XAI](https://img.shields.io/badge/XAI-GradCAM%2B%2B-blueviolet?logo=openai&logoColor=white)
![Guided%20Grad-CAM](https://img.shields.io/badge/XAI-Guided%20GradCAM-green?logo=tensorflow&logoColor=white)
![Score-CAM](https://img.shields.io/badge/XAI-ScoreCAM-teal?logo=pytorch&logoColor=white)
![CNN](https://img.shields.io/badge/Model-VGG16%20%7C%20ResNet50-red)

**MedXplain** is an ML-based project that detects **Alzheimer’s Disease, Glaucoma, and Pneumonia** from medical images and explains model predictions using **XAI techniques** like Grad-CAM++ and Score-CAM.

---

## ✨ Features

* Disease Detection using **VGG16** and **ResNet50** CNN models.
* **Explainable AI (XAI):** Visual explanations using **Grad-CAM++** and **Score-CAM**.
* Supports **three diseases** trained and evaluated separately.
* Achieved up to **92% accuracy** with visual interpretability heatmaps.

---

## 🧠 Tech Stack

* **ML Framework:** TensorFlow, Keras
* **Explainability:** Grad-CAM++, Score-CAM
* **Data Analysis:** NumPy, Pandas, Matplotlib, Seaborn
* **Dataset Sources:** Kaggle (Pneumonia), ADNI (Alzheimer’s), DRISHTI-GS (Glaucoma)

---

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

*MedXplain – Illuminating the Black Box of Medical AI*
