# 🌫️ Fog vs Smog Detection using Deep Learning 🚀

<p align="center">
  <img src="https://img.shields.io/badge/AI-Computer%20Vision-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Model-CNN%20%7C%20MobileNetV2%20%7C%20EfficientNet-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Accuracy-97%25-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-orange?style=for-the-badge">
</p>

<p align="center">
  <img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="300">
</p>

---

## 📌 Project Overview

An **AI-powered Computer Vision system** that classifies environmental images into:

- 🌫️ **Foggy**
- 🌤️ **Clear / Smog**

This project implements a **complete deep learning pipeline** from raw dataset → preprocessing → training → evaluation → model comparison.

---

## 🎯 Objectives

✔️ Detect atmospheric conditions using images  
✔️ Perform detailed **EDA (Exploratory Data Analysis)**  
✔️ Apply **image preprocessing & augmentation**  
✔️ Train multiple **Deep Learning models**  
✔️ Compare performance using real metrics  

---

## 🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,opencv,numpy,pandas,sklearn" />
</p>

---

## ⚙️ Workflow Pipeline

```mermaid
graph TD;
    A[Dataset] --> B[EDA]
    B --> C[Data Cleaning]
    C --> D[Preprocessing]
    D --> E[Data Augmentation]
    E --> F[Train/Test Split]
    F --> G[Model Training]
    G --> H[Evaluation]
    H --> I[Model Comparison]
```

---

## 📂 Dataset Info

| Feature | Details |
|--------|--------|
| Source | Kaggle |
| Classes | Clear, Foggy |
| Images | ~2300+ |
| Type | Image Classification |

---

## 🔍 Exploratory Data Analysis

✔️ Class distribution visualization  
✔️ Image brightness & size analysis  
✔️ RGB histogram comparison  
✔️ Data quality checks (duplicates, corruption)

---

## 🛠️ Preprocessing

- 📏 Resize → **224x224**
- 🎨 Convert → RGB
- 🔢 Normalize → [0,1]
- 🔄 Augmentation:
  - Flip
  - Rotation
  - Zoom
  - Brightness

---

## 🤖 Models Used

| Model | Type | Description |
|------|------|------------|
| 🧱 Custom CNN | Baseline | Built from scratch |
| ⚡ MobileNetV2 | Transfer Learning | Lightweight & fast |
| 🚀 EfficientNetB0 | Transfer Learning | High performance |

---

## 📊 Results

<p align="center">
  <img src="https://img.shields.io/badge/Custom%20CNN-96.8%25-blue">
  <img src="https://img.shields.io/badge/MobileNetV2-97.1%25-green">
  <img src="https://img.shields.io/badge/EfficientNetB0-~97%25-yellow">
</p>

✔️ High accuracy across all models  
✔️ Transfer learning models performed best  
✔️ Strong generalization on unseen data  

---

## 📈 Evaluation Metrics

- ✅ Accuracy  
- 🎯 Precision  
- 🔁 Recall  
- 📊 F1-Score  
- 🔲 Confusion Matrix  

---

## 🚀 How to Run

### 🔹 Clone Repo
```bash
git clone https://github.com/your-username/fog-smog-detection.git
cd fog-smog-detection
```

### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Run Project
```bash
python smog_or_fog_detection.py
```

---

## 📁 Outputs Generated

📊 EDA Visualizations  
📄 CSV Reports  
🖼️ Image Analysis Graphs  
📦 Preprocessed Dataset  
🤖 Trained Models  
📉 Evaluation Reports  

---

## 🔮 Future Improvements

- 🌐 Deploy using **Streamlit / Flask**
- 📷 Real-time camera detection
- 🌍 Smart city integration
- 🤖 Edge AI deployment (ESP32 / IoT)

---

## 💡 Use Cases

🏙️ Smart Cities  
🌫️ Pollution Monitoring  
🚗 Autonomous Driving  
🌦️ Weather Detection Systems  

---

## 👨‍💻 Author

**Itqa Akhlaq**  
🎓 BS Information Technology  
🤖 AI | ML | Computer Vision Enthusiast  

---

## ⭐ Support

If you like this project:

⭐ Star this repo  
🍴 Fork it  
📢 Share it  

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=120&section=footer"/>
</p>
