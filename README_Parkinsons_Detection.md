# 🧠 Parkinson’s Disease Detection Web App

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
![Login Page](docs/screenshots/login.png)

### 📝 Registration Page
![Registration](docs/screenshots/register.png)

### 🏠 Home Dashboard
![Dashboard](docs/screenshots/dashboard.png)

### 🌀 Spiral Drawing Input
![Spiral Drawing Input](docs/screenshots/spiral_input.png)

### 🎤 Voice Input
![Voice Input](docs/screenshots/voice_input.png)

### 📊 Prediction Results
![Prediction Page](docs/screenshots/prediction.png)

> **Note:** Screenshots should be extracted from the project UI or presentation and placed in `docs/screenshots/`.

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

## 📬 Contact
If you'd like to discuss my work or explore collaboration opportunities:  
**Email:** your.email@example.com  
**LinkedIn:** [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
