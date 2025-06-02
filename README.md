# 🧠 ML\_Project — Automated Street Hole Recognition using Machine Learning

This repository contains the full implementation of our **machine learning and deep learning project and paper**:
**"Automated Street Hole Recognition Using Machine Learning: A Comparative Analysis of Classification Models"**
Conducted as part of the CSCI417/ECEN425: Machine Intelligence course at Nile University.

## 📌 Project Overview

Poor road conditions, such as potholes and surface damage, pose significant risks to public safety and transportation efficiency. Traditional inspection methods are expensive, time-consuming, and limited in scale.

In this project, we developed a system for **automated street hole detection** using image-based classification. We used diverse datasets from multiple countries and environments, trained and compared multiple models, and built a GUI for user-friendly deployment.

---

## 🧪 Models Implemented

We evaluated the following machine learning models:

* ✅ **Convolutional Neural Network (CNN)** – Highest accuracy (97%)
* ✅ **Random Forest** – 94% accuracy, 95% precision
* ✅ **Logistic Regression**
* ✅ **K-Nearest Neighbors (KNN)**
* ✅ **Naive Bayes**

---

## 📊 Dataset Details

* 18,165 street images
* 12,300 features per image (normalized pixel values)
* Includes data from **Germany, Netherlands, India**, and **AI-generated images**
* Enhanced using **data augmentation** for generalization

---

## 🖥️ GUI Features

* Upload and analyze images
* Real-time detection results with confidence scores
* Visual bounding box overlays
* Exportable reports for maintenance use

---

## 🔧 Tech Stack

* Python
* Scikit-learn
* TensorFlow / Keras
* OpenCV
* Tkinter (for GUI)

---

## 📈 Results

| Model         | Accuracy | Precision | Recall |
| ------------- | -------- | --------- | ------ |
| CNN           | 97.00%   | —         | —      |
| Random Forest | 94.00%   | 95.00%    | 90.00% |
| Logistic Reg. | 90.97%   | 88.00%    | 91.00% |
| KNN           | 86.89%   | 79.36%    | 92.99% |
| Naive Bayes   | 79.07%   | —         | —      |

---

## 📄 Paper

Check out the full paper in the `paper/` directory or [click here to view the PDF](file:///C:/Users/mousa/Downloads/Street-Hole-Recognition.pdf).

---

## 🤝 Acknowledgment

Special thanks to:

* 🎓 **Dr. Amal Fouad** – for her guidance throughout the project
* 👩‍💻 **Eng. Amira Tarek** – for technical insights and support
* 👨‍💻 **Mohamed Amir** – my project partner and co-author

---

## 💡 Open for Feedback

Feel free to open issues or pull requests. Suggestions for improvements or extensions (e.g., multi-class classification, real-time video input, mobile app deployment) are welcome!

---

## 🔗 Connect

If you find this useful or want to collaborate:

* LinkedIn: [Your LinkedIn Profile](www.linkedin.com/in/mousa-ashraf-5250641b5)
* GitHub: [Your GitHub Username](https://github.com/MousaAshraf)

---
