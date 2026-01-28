
# 🧠 Alzheimer’s Disease Detection Using Transfer Learning

This project presents a **deep learning–based approach for early detection of Alzheimer’s disease** from brain MRI images. By leveraging **transfer learning with pre-trained CNN models**, the system achieves reliable classification while reducing training time. A **Flask-based web application** is used to provide real-time predictions through a simple user interface.

---

## 🔍 Project Overview

Alzheimer’s disease is a progressive neurological disorder that affects memory and cognitive abilities. Early diagnosis is critical for effective treatment and disease management. This project aims to **automate the detection process** using medical image analysis, supporting healthcare professionals and researchers.

---

## 🧠 Models & Methodology

The system uses transfer learning with the following convolutional neural network architectures:

* **MobileNet** – Efficient and lightweight
* **NASNet** – High-performance architecture
* **EfficientNet** – Optimized scaling for accuracy

MRI images are preprocessed, normalized, and passed through the trained model to predict Alzheimer’s presence.

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* Flask
* NumPy, Pandas
* HTML, CSS

---

## 📁 Project Structure

```
Alzheimer_Detection/
├── app.py
├── alzheimer_detection.h5
├── requirements.txt
├── README.md
```

---

## ⚙️ How to Run

```bash
pip install -r requirements.txt
python app.py
```

Open your browser at: `http://127.0.0.1:5000/`
