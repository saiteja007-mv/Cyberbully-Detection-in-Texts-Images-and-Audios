# 🚀 Cyberbullying Detection in Texts, Images, and Audios  

Detecting cyberbullying in online content using Machine Learning & Deep Learning techniques.  

![Flow of Events](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/9b0049ef-0c40-488a-beae-6b72951891c4)  

---

## 🌜 Table of Contents  
- [Introduction](#introduction)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Datasets](#datasets)  
- [Evaluation Metrics](#evaluation-metrics)  
- [Results](#results)  
- [Conclusion](#conclusion)  
- [Future Work](#future-work)  
- [References](#references)  

---

## 📝 Introduction  
Cyberbullying is a growing concern in social media and online communities. This project leverages **Machine Learning & Deep Learning** models to detect cyberbullying across multiple data formats:  
- **Text** using **Bidirectional LSTM (Bi-LSTM)**  
- **Images** using **Convolutional Neural Networks (CNN)**  
- **Audio** using **Speech Recognition and NLP**  

The project aims to provide a **high-accuracy cyberbullying detection system** to ensure a safer online environment.  

---

## 🌟 Features  
✅ Detection of cyberbullying in **text, images, and audio**  
✅ **Ensemble approach** combining **Bi-LSTM** and **CNN** for better accuracy  
✅ **Multi-modal** data support  
✅ Performance evaluation using **accuracy, precision, recall, and confusion matrix**  
✅ Potential extension to **video-based analysis**  

---

## ⚙️ Installation  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios.git
cd Cyberbully-Detection-in-Texts-Images-and-Audios
pip install -r requirements.txt
```

Make sure you have Jupyter Notebook installed:  
```bash
pip install notebook
```

---

## 🚀 Usage  
1️⃣ Open **Jupyter Notebook**  
```bash
jupyter notebook
```
2️⃣ Navigate to the **notebook files** for text, image, and audio analysis  
3️⃣ **Prepare your dataset** with labeled **cyberbullying** and **non-cyberbullying** content  
4️⃣ Run the cells in the notebook to **train the models**  
5️⃣ View **evaluation metrics and predictions**  

---

## 📂 Datasets  
### 📝 **Text Dataset**  
- **File:** `twitter.csv`  
- **Content:** Labeled tweets for cyberbullying detection  
![Text dataset](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/a1c35e71-dce8-4914-ab75-395de63827b1)  

### 🖼️ **Images Dataset**  
- **Folder:** `Images_dataset`  
- **Content:** Cyberbullying-related images  
![Images dataset](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/ad8e174c-e567-48b3-8e32-232022ef938e)  

### 🔊 **Audio Dataset**  
- **Folder:** `audios`  
- **Content:** Audio samples labeled for cyberbullying  
![Audio dataset](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/d630e382-9665-4d1b-8938-33458528f8d7)  

---

## 📊 Evaluation Metrics  
The models are evaluated based on:  
- **💢 Accuracy:** Percentage of correctly classified instances  
- **📍 Precision:** Ratio of correctly predicted positive observations  
- **📋 Recall:** Proportion of actual positives correctly identified  
- **📊 Confusion Matrix:** Visual representation of true vs. predicted labels  

![Acc_pre_bar_epochs](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/0fd407ca-1e90-4c4c-8ed5-5ee833dcadf4)  
![Text_Metrics_vs_epochs](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/d95b4433-0af2-47cb-a416-bb5b156409a5)  
![Confusion_matrix_text](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/b49a37c2-ecc4-4f92-87b9-5e1a9fbd5f36)  

---

## 📈 Results  
- **High accuracy** achieved for text and image-based cyberbullying detection  
- The **ensemble approach (Bi-LSTM + CNN)** improved precision & recall  
- Future improvements can enhance **audio analysis**  

---

## 🎯 Conclusion  
This project demonstrates that **deep learning models can effectively detect cyberbullying** across different media types. The **ensemble approach** combining **Bidirectional LSTM and CNN** significantly improves accuracy. However, further enhancements are required for **real-time video analysis**.  

---

## 🔮 Future Work  
🔹 **Integrate video analysis** using **object recognition and context analysis**  
🔹 **Enhance speech recognition** for **better audio-based detection**  
🔹 **Deploy as an API or web application** for **real-time cyberbullying detection**  
🔹 **Improve dataset diversity** to enhance model generalization  

---

## 📚 References  
📖 V. Subrahmanian and S. Kumar, *Predicting human behavior: The next frontiers*, Science, vol. 355, no. 6324, p. 489, 2017.  

📖 H. Lauw, J. C. Shafer, R. Agrawal, and A. Ntoulas, *Homophily in the digital world: A Live Journal case study*, IEEE Internet Comput., vol. 14, no.2, pp. 15–23, 2010.  

📖 Arindam Mandal, Sriparna Saha, Alexandar Ferworn, *A Hybrid Model for Cyberbullying Detection on Facebook*.  

