# 🧑‍💻 Face Recognition using Computer Vision and Deep Learning

## 📝 Project Overview  
This project implements a **Face Recognition System** using **Computer Vision (CV)** and **Deep Learning** techniques.  
The system can detect, recognize, and classify faces from images. Applications include **security authentication, attendance systems, and personalized access control**.  

---

## 📊 Dataset  
- Source: **LFW (Labeled Faces in the Wild) dataset**  
- Description: A benchmark dataset of **13,000+ images** of faces collected from the web, labeled with the person’s name.  
- Usage: Images were preprocessed (resizing, grayscale, normalization) before training.  

---

## 🔬 Methodology  

### 1. Data Preprocessing  
- Resizing images  
- Converting to grayscale  
- Normalization  
- Face detection with **Haar Cascade Classifier**  

### 2. Feature Extraction  
- Local Binary Patterns Histograms (LBPH)  

### 3. Models Implemented  
- **LBPH Face Recognizer** (OpenCV)  
- **Deep Learning Model**: CNN built with Keras/TensorFlow  

### 4. Model Evaluation  
- Accuracy score on test dataset  
- Confusion Matrix  
- Visualization of correctly/incorrectly classified images  

---

## 📈 Results  
| Model                  | Accuracy |
|-------------------------|----------|
| LBPH Classifier (OpenCV) | 85.4% |
| CNN (Keras/TensorFlow)   | **94.6%** |

- The **CNN model outperformed LBPH**, achieving **94.6% accuracy**.  
- Haar Cascade successfully detected faces in real-time images.  

