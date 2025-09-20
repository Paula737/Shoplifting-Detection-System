# 🛒 Shoplifting Detection System 

An **AI-powered video surveillance system** that detects shoplifting activities using **deep learning**.  
This project leverages **video classification with MobileNetV2** and **sequence modeling** to analyze surveillance footage, enabling real-time detection and prevention of retail theft.  

---

## 📖 Overview  

Shoplifting poses a major challenge to retailers.  
This system processes CCTV video streams and automatically classifies behavior into:  

- **Non-Shoplifter**  
- **Shoplifter**  

✅ Contributions:  
- Preprocessing pipeline for video frame extraction & deduplication.  
- MobileNetV2-based **video classification model** with temporal pooling.  
- Achieved robust test accuracy with confusion matrix and evaluation metrics.  
- Feature extraction for similarity analysis (cosine similarity & embeddings).  
- Deployed as a **Django web application** for real-time monitoring.  

---

## 🎯 Objectives  

- **Data Handling**  
  - Extract frames from raw surveillance videos.  
  - Remove near-duplicate frames using difference thresholding.  
  - Cache preprocessed video frames as `.npy` files for faster training.  

- **Model Development**  
  - TimeDistributed MobileNetV2 backbone.  
  - Global average pooling over time dimension.  
  - Fully connected layers for binary classification.  
  - Optimized with binary crossentropy and Adam optimizer.  

- **Evaluation**  
  - Accuracy & loss curves across epochs.  
  - Classification report (precision, recall, F1-score).  
  - Confusion matrix visualization.  

---

## 🛠️ Technology Stack  

- **Language:** Python 3.x  
- **Deep Learning Framework:** TensorFlow / Keras  
- **Libraries:** OpenCV, NumPy, Scikit-learn, Seaborn, Matplotlib  
- **Backend:** Django  
- **Deployment:** Docker + Django REST Framework  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>  

---

👨‍💻 Author

✨ 𝑬𝒏𝒈. 𝒫𝒶𝓊𝓁𝒶 𝐻𝒶𝓃𝓃𝒶 𝒩𝒶𝑔𝓊𝒾𝒷 ✨

📌 “Knowledge is power. Applying AI to security transforms surveillance into intelligent protection.”  

