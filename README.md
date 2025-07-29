# Diabetic Retinopathy Detection using CNN

**Research Internship Project**  
**Institute**: Birla Institute of Technology, Mesra  
**Mentor**: Prof. Vandana Bhattacharya, CSE Department  
**Duration**: May 2025 – July 2025

---

## 🧠 Project Overview

This project focuses on the detection and classification of **Diabetic Retinopathy (DR)** using Convolutional Neural Networks (CNNs). Various preprocessing techniques and model optimizations were explored to improve detection accuracy and robustness.

---

## 📌 Key Contributions

- 🏥 **Image Preprocessing**:
  - Applied **CLAHE** and **Ben Graham’s normalization** to enhance vessel visibility.
  - Result: Reduced training time by **50%**.

- 🧠 **Model Enhancements**:
  - Used **channel attention** and **spatial attention** mechanisms.
  - Integrated **Squeeze-and-Excitation (SE) blocks**.
  - Applied **Focal Loss** for class imbalance.

- 🎯 **Performance**:
  - 81% accuracy using attention.
  - Improved to **85%** with SE and focal loss.

---

## 🗂️ Files

- `06_without-classweights-and-lossfunc-change.ipynb`
- `19_preprocessed-model_loss_func_change.ipynb`
- `hybrid-custommodel.ipynb`
- `preprocessed-improved-384.ipynb`

---

## ⚙️ Environment

```bash
Python 3.8+
TensorFlow / Keras
OpenCV
NumPy, Pandas, Matplotlib
