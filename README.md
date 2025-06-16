# 🖼️ Image Classification with Teachable Machine

This project demonstrates how to train a real-time image classification model without writing any code, using **Google's Teachable Machine**. It classifies images into two categories using webcam or uploaded inputs and displays prediction confidence instantly.

---

## 🔍 Objective

To create a no-code machine learning model that can accurately distinguish between two visual classes (e.g., apples vs bananas, thumbs up vs thumbs down) using Teachable Machine’s browser-based platform.

---

## 📁 Dataset

- **Source**: Self-collected via webcam and/or uploaded images  
- **Classes**: Example — `Apple` and `Banana`  
- **Size**: ~30 images per class (recommended for training)

> You can also use curated image datasets from sources like [Unsplash](https://unsplash.com/), [Pexels](https://pexels.com), or [Kaggle Fruits 360](https://www.kaggle.com/datasets/moltean/fruits).

---

## 🛠️ Tools & Platforms

- **[Teachable Machine](https://teachablemachine.withgoogle.com/)** by Google  
- **TensorFlow.js** (optional for export)  

---

## 💡 Key Learnings

- Teachable Machine enables rapid prototyping for image classification tasks
- No coding required — great for beginners, students, and educators
- Models can be exported and embedded in real-world applications

---

## 📁 Folder Structure

```
├── Apples/ # Class 1 images
├── Bananas/ # Class 2 images
├── converted_savedmodel/ # Exported TensorFlow model
├── LICENSE
└── README.md
```
