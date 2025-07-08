# 🧠 Skin Cancer Classification with Deep Learning

This project applies Convolutional Neural Networks (CNNs) and Transfer Learning to classify skin cancer from dermoscopic images, focusing mainly on **Melanoma** and **Melanocytic Nevi**. These two conditions are the most common and clinically significant in the dataset.

> 🔬 Achieved **up to 92% accuracy** using models like ResNet50 and MobileNetV2.

---

## 📂 Dataset

- The dataset includes dermoscopic images categorized into 7 classes, but this project primarily focuses on:
  - **Melanoma (mel)** – Dangerous skin cancer type
  - **Melanocytic Nevi (nv)** – Common, mostly benign mole

---

## 🛠️ Tech Stack

- **Frameworks:** TensorFlow, Keras
- **Models Used:** Custom CNN, ResNet50, MobileNetV2, EfficientNetB0
- **Tools:** NumPy, Matplotlib, Seaborn
- **Platform:** Jupyter Notebook / Google Colab

---

## 📊 Results

| Model          | Accuracy |
|----------------|----------|
| Custom CNN     | 85%      |
| ResNet50       | 92%      |
| MobileNetV2    | 91%      |

✅ Evaluation: **F1-score**, **Precision**, **Recall**, and **Confusion Matrix**

## 📌 Highlights

- Focused analysis on **Melanoma vs Nevus** classification.
- Applied **transfer learning** for improved accuracy.
- Visualized performance using confusion matrix and learning curves.

---

## 🚀 Future Improvements

- Class balancing via augmentation
- More fine-tuning on pretrained models
- Expand focus to other skin lesion types
