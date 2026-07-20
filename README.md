<div align="center">

# 🌾 Weed Detection in Wheat Crops using Computer Vision

### AI-powered Precision Agriculture using Deep Learning

Detects **Weed**, **Wheat**, and **Other Objects** from field images using a custom-trained **ResNet18** model with explainable AI (Grad-CAM).

<img src="assets/banner.png" width="100%"/>

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![License](https://img.shields.io/badge/License-MIT-success)

</div>

---

# 🌱 Overview

Weed infestation significantly reduces crop yield by competing with wheat for nutrients, water and sunlight.

Traditional weed detection methods are:

- Time consuming
- Labour intensive
- Error prone
- Expensive
- Environmentally harmful due to excessive herbicide usage

This project introduces an intelligent Computer Vision system capable of identifying

✅ Wheat

✅ Weed

✅ Other Objects

from uploaded field images using Deep Learning.

---

# ✨ Features

✔ Multi-class Image Classification

✔ Custom ResNet18 Model

✔ PyTorch Training Pipeline

✔ Dataset Augmentation

✔ Grad-CAM Explainability

✔ Flask Web Application

✔ Image Upload Interface

✔ Real-time Predictions

✔ Early Stopping

✔ Data Bias Improvement

✔ Responsive UI

---

# 🧠 Model Pipeline

```text
Dataset
      │
      ▼
Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
ResNet18 Training
      │
      ▼
Validation
      │
      ▼
Grad-CAM
      │
      ▼
Flask Deployment
      │
      ▼
Prediction
```

---

# 📂 Dataset

The dataset contains three classes.

| Class | Description |
|--------|-------------|
| 🌾 Wheat | Healthy wheat crop |
| 🌿 Weed | Weed species |
| 🚗 Other | Any non-wheat image |

Dataset preprocessing includes

- Resize
- Normalization
- Random Flip
- Rotation
- Color Jitter
- Balanced Augmentation

---

# 🚀 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Backend |
| PyTorch | Deep Learning |
| Torchvision | Data Pipeline |
| OpenCV | Image Processing |
| Flask | Web Framework |
| HTML/CSS | Frontend |
| Grad-CAM | Explainable AI |
| NumPy | Numerical Computing |

---

# 🏗 Architecture

```
User Uploads Image
        │
        ▼
Image Preprocessing
        │
        ▼
ResNet18 Model
        │
        ▼
Prediction
        │
 ┌──────┼────────┐
 │      │        │
 ▼      ▼        ▼
Weed  Wheat   Others
```

---

# 📊 Performance

### Classification Accuracy

⭐ ~92%

### Prediction Time

⚡ 2–3 Seconds

### Classes

- Weed
- Wheat
- Others

---

# 🔥 Key Highlights

✅ Improved previous biased model

✅ Better preprocessing pipeline

✅ Three-class classification

✅ Real-time deployment

✅ Explainable AI using Grad-CAM

✅ Lightweight deployment

---

# 📈 Future Scope

- Drone Integration

- Mobile Application

- IoT-enabled Smart Farming

- Real-time Video Detection

- Edge AI Deployment

- Multiple Crop Support


---

# 💻 Run

```bash
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

# 📁 Project Structure

```
WeedDetection/

│── app.py
│── best_model.pth
│── templates/
│── static/
│── dataset/
│── notebook/
│── model/
│── utils/
│── requirements.txt
│── README.md
```


---

# ⭐ If you like this project

Give this repository a ⭐ 
