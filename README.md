# 🔍 Deepfake Face Detection

A deep learning system to detect AI-generated fake faces using 
Transfer Learning and Explainable AI.

## 🚀 Live Demo
👉 [Try it here](https://huggingface.co/spaces/tanishka-shekar/deepfake-detector)

## 🧠 Tech Stack
- Python, TensorFlow, Keras
- MobileNetV2 (Transfer Learning)
- Grad-CAM (Explainable AI)
- Gradio (Web App)

## 📊 Dataset
140,000 Real and Fake Faces (Kaggle)

## 📈 Results
- ~80% validation accuracy
- Grad-CAM heatmaps for explainability
- Live deployed web application

## 🏗️ Architecture
Input → MobileNetV2 → GlobalAveragePooling → Dense → Sigmoid

## 📁 Project Structure
- `DEEP_LEARNING.ipynb` - Main training notebook
- `app.py` - Gradio web application
- `requirements.txt` - Dependencies
