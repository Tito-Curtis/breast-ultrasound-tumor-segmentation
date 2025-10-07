# Breast Ultrasound Tumor Segmentation 🩺

This project implements a **U-Net convolutional neural network** for segmenting tumor regions in breast ultrasound images.  
It leverages the [Breast Ultrasound Images Dataset](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset), including *normal*, *benign*, and *malignant* cases.

---

## 🧠 Project Overview
- **Goal:** Automate the detection and segmentation of breast tumors from ultrasound images.
- **Model:** U-Net built with TensorFlow/Keras.
- **Techniques:** Data augmentation, balancing, Dice and IoU metrics for evaluation.
- **Visualization:** Overlay of predicted vs. ground-truth masks.

---

## 📊 Dataset
The dataset contains:
| Category | Images | Masks |
|-----------|---------|-------|
| Normal | 133 | 133 |
| Benign | 437 | 454 |
| Malignant | 210 | 211 |

---

## ⚙️ Pipeline
1. Data loading and preprocessing  
2. Data augmentation and balancing  
3. Model building (U-Net)  
4. Training and validation  
5. Evaluation with Dice, IoU, precision, recall  
6. Visualization of segmentation results

---

## 🧾 Results
- Achieved high Dice coefficient and IoU on validation set.
- Model successfully delineates tumor boundaries across categories.

---

## 💻 Technologies
- **Python**, **TensorFlow/Keras**, **NumPy**, **Matplotlib**, **OpenCV**, **Google Colab**

---

## 🔗 Reference
Dataset: [Breast Ultrasound Images Dataset (Kaggle)](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)
