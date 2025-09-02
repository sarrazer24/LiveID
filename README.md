# 🪪 Face ID Verification with Liveness Detection

## 📌 Project Description

This project implements a **face recognition system** that verifies a person’s identity by comparing an official **ID photo** with a **selfie**.
It also includes basic **liveness detection** to ensure the selfie belongs to a real, live person (not a photo or spoof).

Built with **Python, Deep Learning models, and Kaggle datasets**.

---

## 📂 Dataset

* Source: [Kaggle Selfie-ID Images Dataset](https://www.kaggle.com/)
* The dataset contains pairs of **ID images** and **selfies** for the same individuals.
* Format: `selfie_id.csv` links each ID photo with corresponding selfie(s).

---

## ⚙️ Features

* ✅ **Face embedding extraction** using pre-trained models (e.g., ArcFace, FaceNet).
* ✅ **ID ↔ Selfie verification** with similarity scoring.
* ✅ **Basic liveness detection** to reduce spoofing attempts.
* ✅ **Evaluation metrics** (accuracy, false acceptance rate, false rejection rate).
* ✅ **Runs on Kaggle or locally** (with dataset download).

---

## 🚀 How to Run

### 1. On Kaggle

* Open the notebook in Kaggle.
* Dataset will be available under `/kaggle/input/`.
* Run all cells to reproduce results.

### 2. Locally (VS Code / Jupyter)

* Clone this repo:

  ```bash
  git clone https://github.com/yourusername/face-id-verification.git
  cd face-id-verification
  ```
* Install dependencies:

  ```bash
  pip install -r requirements.txt
  ```
* Place dataset in `./data/` and update paths in code.
* Run the notebook or Python scripts.

---

## 🧠 Tech Stack

* Python 🐍
* DeepFace / FaceNet / ArcFace
* OpenCV
* scikit-learn
* Pandas, NumPy, Matplotlib

---

## 📊 Results

* ID–selfie matching achieved **X% accuracy** on the dataset.
* Liveness checks successfully filtered out basic spoofing attempts.
* Future work: improve advanced liveness detection with video sequences.

---

## 📌 Future Improvements

* Support video-based liveness (blink/pose detection).
* Integration with real-time webcam input.
* Deploy as a web or mobile API for authentication.

---

## 👩‍💻 Author

Developed by **[Sarra Zerguerras](https://github.com/sarrazer24 )**
AI & Data Science Student | Backend & Mobile Developer | UI/UX Designer

