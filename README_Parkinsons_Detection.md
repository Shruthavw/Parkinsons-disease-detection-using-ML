# 🧠 Parkinson’s Disease Detection Using ML

**Tech Stack:** Python (Flask), Convolutional Neural Networks (CNN), HTML/CSS/JS, Kaggle Datasets, MySQL  
**Role:** Full-Stack Developer | Machine Learning Engineer  
**Status:** Working Prototype – Presented & Approved ✅  

---

## 💡 Why This Project Matters  
Parkinson’s Disease (PD) is a progressive neurodegenerative disorder, and **early detection is critical** for improving patient outcomes. Traditional diagnosis relies heavily on subjective clinical assessments, which often delays intervention.  
This project leverages **machine learning** to detect early signs of PD from **spiral drawings** and **voice recordings**, making screening more accessible, faster, and potentially more accurate.

---

## 📌 Overview  
The Parkinson’s Disease Detection Web App allows users to:  
- Register and securely log in.  
- Upload **spiral drawing images** and **voice recordings**.  
- Receive predictions on Parkinson’s likelihood (Low / Medium / High).  
- Access educational resources on Parkinson’s Disease.  

The ML backend uses **CNN models** trained on medical datasets to detect subtle motor and speech pattern deviations indicative of PD.

---

## 🎯 Objectives
- Build a secure, accessible web platform for PD risk assessment.  
- Integrate ML models for multi-modal (image + audio) analysis.  
- Provide clear, user-friendly results for informed decision-making.  

---

## 🛠 My Contributions
- **Backend Development:** Flask-based API for handling image & audio uploads, preprocessing, and ML inference.  
- **Machine Learning:** Implemented and trained CNN models for spiral and voice datasets; optimized for accuracy and generalization.  
- **Frontend UI:** Developed a responsive, intuitive interface for patient interaction.  
- **Security:** Implemented session management, authentication, and secure data handling.  
- **Data Handling:** Processed Kaggle Parkinson’s Speech Dataset & spiral datasets for model training.  
- **Integration:** Combined audio and image ML predictions into a unified risk assessment.

---

## 📂 System Architecture
```plaintext
User → Web UI (HTML/CSS/JS) → Flask API → Preprocessing → CNN Models → Prediction → UI Results
```

---

## 🖼 Screenshots

### 🔑 Login Page
<img width="520" height="293" alt="image" src="https://github.com/user-attachments/assets/3f69b6d3-9811-499f-9e8a-a6498694fc8f" />


### 📝 Registration Page
<img width="522" height="324" alt="image" src="https://github.com/user-attachments/assets/3da9af77-3ab7-4093-a07b-a49783d2b2a8" />


### 🏠 Home Page
<img width="582" height="294" alt="image" src="https://github.com/user-attachments/assets/77a12809-1428-4d42-b539-219ad8fbfaaa" />


### 📝 Dashboard Page
<img width="558" height="297" alt="image" src="https://github.com/user-attachments/assets/189c9f3f-996e-4783-b119-af88a640eaba" />


### 🌀 Spiral Drawing Input
<img width="634" height="326" alt="image" src="https://github.com/user-attachments/assets/00c2843e-0445-4b20-b7dd-c7e5c777c648" />


### 🎤 Voice Input
<img width="634" height="322" alt="image" src="https://github.com/user-attachments/assets/2965ffb9-2c49-45d4-b6b2-abcef9fddc72" />


### 📊 Prediction Results
<img width="634" height="306" alt="image" src="https://github.com/user-attachments/assets/65a6c44d-b4d1-4240-ba9a-a265b23f293f" />



---

## 📊 Datasets Used
1. **Parkinson Speech Dataset with Multiple Types of Sound Recordings**  
   - Source: Kaggle  
   - Includes sustained vowels, numbers, words, and sentences from PD and healthy individuals.  

2. **Spiral Drawing Dataset**  
   - Spiral sketches from healthy and PD-affected individuals for motor control analysis.  

---

## 🤖 Algorithms
- **Convolutional Neural Networks (CNN)** for both spiral drawing and voice signal classification.  
- **Preprocessing:** Audio feature extraction (MFCCs), image resizing, normalization.  
- **Pooling Layers:** Dimensionality reduction to prevent overfitting.  
- **Fully Connected Layers:** Final classification into PD / Healthy categories.

---

## 🚀 Results
- Achieved high prediction accuracy for both datasets in testing phase.  
- Provided **clear & interpretable** results for users.  
- Demonstrated feasibility of a multi-modal PD screening tool.  

---

## 📈 Future Scope
- Real-time analysis with wearable device integration.  
- Continuous monitoring & progression tracking.  
- AI-based personalized treatment suggestions.  
- Multi-language voice input support.

---

## 🔒 Disclaimer
Due to data privacy and academic project policies, full production deployment is not public.  
This repository contains **documentation, screenshots, and selected code segments** for portfolio purposes.

---
