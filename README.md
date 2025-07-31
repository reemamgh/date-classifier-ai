# Date Type Classification Using Teachable Machine 🍯📸

This is a simple image classification project built using [Teachable Machine](https://teachablemachine.withgoogle.com/) by Google. The goal is to classify different types of dates using a custom-trained model, which was later exported as a Keras model using TensorFlow.

## 📌 Project Overview

The model is trained to classify images of dates into the following four categories:

- Sukkari (السكري)
- Saqei (الصقعي)
- Khalas (الخلاص)
- Ajwa (العجوة)

After training, the model was tested and achieved **100% accuracy** on the test samples.

## 🧠 Tools & Technologies

- [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)
- TensorFlow
- Keras
- Python

## 🗂️ Dataset Details

A total of **26 images** were used for training **each class**, resulting in **104 training images** overall.

## 🧪 Model Testing

The exported Keras model was tested locally with new images and performed very well, successfully predicting the correct type of date.

## 🚀 How to Use

1. Download the model files (`model.h5`, `labels.txt`, etc.).
2. Load the model in your Python environment.
3. Run predictions on any image of dates.
4. The model will return the predicted class name.

## 📷 Example 
<img width="1438" height="790" alt="Screenshot 2025-07-31 at 5 18 32 AM" src="https://github.com/user-attachments/assets/13b5623c-d89c-4942-a802-eb8402162b31" />
## ⚠️ Notes

- This project was built for educational purposes.
- Accuracy and performance can be improved by increasing the dataset size and diversity.

---

## 👩🏻‍💻 Developer
**Reema M. Al-Ghamdi**  
