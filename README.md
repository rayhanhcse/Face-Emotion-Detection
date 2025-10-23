


<h1 align="center">
  <span style="background: linear-gradient(to right, #ff416c, #ff4b2b); -webkit-background-clip: text; color: transparent;">
    😃 Face Emotion Detection
  </span>
</h1>

<p align="center">
  <strong>Detect human emotions in real-time using Deep Learning & CNN</strong>
</p>

<p align="center">
  <a href="https://github.com/rayhanhcse/face-emotion-detection">
    <img src="https://img.shields.io/badge/GitHub-rayhanhcse-181717?style=for-the-badge&logo=github" alt="GitHub Badge"/>
  </a>
  <a href="mailto:rayhanhcse@gmail.com">
    <img src="https://img.shields.io/badge/Email-rayhanhcse@gmail.com-D14836?style=for-the-badge&logo=gmail" alt="Email Badge"/>
  </a>
  <a href="https://linkedin.com/in/rayhanchse">
    <img src="https://img.shields.io/badge/LinkedIn-rayhanchse-0077B5?style=for-the-badge&logo=linkedin" alt="LinkedIn Badge"/>
  </a>
  <img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python" alt="Python Badge"/>
  <img src="https://img.shields.io/badge/TensorFlow-Keras-orange?style=for-the-badge&logo=tensorflow" alt="TensorFlow Badge"/>
</p>


## 🚀 Overview
**Face Emotion Detection Project** is a real-time emotion recognition system using **Convolutional Neural Networks (CNN)**.  
It classifies facial expressions into multiple emotions like **😀 Happy, 😞 Sad, 😠 Angry, 😮 Surprise, 😐 Neutral**.

---

## 🎯 Features
- 🖼️ Detect emotions from static images or live webcam feed  
- 🧠 CNN-based emotion classification  
- 📊 Real-time visualization  
- ⚡ Lightweight and fast for live applications  

---

## 🗂️ Dataset
**Dataset:** [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013)  
- Image size: 48x48 grayscale  
- Classes: 5  
- Total samples: ~35,000  

---

## 🧠 Model Architecture
```

Input(48x48)
↓
Conv2D + ReLU
↓
MaxPooling
↓
Conv2D + ReLU
↓
MaxPooling
↓
Flatten
↓
Dense + Dropout
↓
Output (Softmax – 5 classes)

```

---

## 🛠️ Tech Stack
| Category | Tools / Libraries |
|----------|------------------|
| Programming | Python 3.10 |
| Deep Learning | TensorFlow / Keras |
| Image Processing | OpenCV |
| Data Handling | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| App Interface | Flask / Streamlit |
| Version Control | Git, GitHub |

---

## 🏗️ Project Structure
```

face-emotion-detection/
│
├── data/                   # Dataset folder
├── models/                 # Saved CNN models
├── notebooks/              # Jupyter notebooks (EDA, model training)
├── src/                    # Source code
│   ├── preprocess.py
│   ├── model.py
│   ├── detect.py
├── app.py                  # Flask/Streamlit app (optional)
├── requirements.txt
└── README.md

````

---

## ⚡ How to Run
### Clone Repo
```bash
git clone https://github.com/rayhanhcse/face-emotion-detection.git
cd face-emotion-detection
````

### Create Environment

```bash
conda create -n emotion python=3.10
conda activate emotion
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Training

```bash
python train.py
```

### Run Real-Time Detection

```bash
python detect.py
```

---

## 📊 Model Performance

| Metric              | Value |
| ------------------- | ----- |
| Accuracy            | 91.2% |
| Loss                | 0.21  |
| Validation Accuracy | 89.5% |

---

## 🌟 Future Enhancements

* Integrate **Transfer Learning** (MobileNetV2, ResNet50)
* Add **real-time emotion tracking with bounding boxes**
* Deploy with **AWS ECR + ECS**
* Build **web dashboard** for live visualization

---

## 👨‍💻 Author

**Rayhan Hussain**
📧 Email: [rayhanhcse@gmail.com](mailto:rayhanhcse@gmail.com)
🌐 GitHub: [rayhanhcse](https://github.com/rayhanhcse)
💼 LinkedIn: [rayhanchse](https://linkedin.com/in/rayhanchse)

---

<p align="center">
  <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="100" alt="Animated Emoji"/>
</p>



* 🌈 **Gradient header**
* 🏷️ **Badges for GitHub, Email, LinkedIn, Python, TensorFlow**
* 😃 **Emojis for emotion classes & sections**
* 🎬 **Animated emoji GIF**


