# CODESOFT-TASK-5

# 🤖 Face Detection and Recognition using OpenCV

This project is part of the **CodSoft Artificial Intelligence Internship – Task 5**. It demonstrates how to detect and recognize human faces using OpenCV with Haar Cascades and the LBPH (Local Binary Pattern Histogram) face recognizer.

---

## 📌 Features

- Face detection using Haar Cascade Classifier.
- Face dataset collection via webcam.
- Training face recognition model using LBPH.
- Real-time face recognition.

---

## 🛠️ Requirements

Install dependencies using:

```
pip install opencv-python numpy pillow
```

## **🗂 Folder Structure**

face_recognition_project/

├── dataset/                     # Captured face images

├── trainer/                     # Trained model

├── 1_capture_faces.py           # Face data collection

├── 2_train_model.py             # Model training

├── 3_recognize_face.py          # Real-time recognition

---

## 🧪 How to Run

**1. Capture Face Images**

```
python 1_capture_faces.py
```
Enter a User ID when prompted.

Press q to stop when 30 images are captured.


**2. Train the Recognizer**

```
python 2_train_model.py
```
Trains and saves the model to trainer/trainer.


**3. Real-Time Face Recognition**

```
python 3_recognize_face.py
```

Recognizes the trained user.

Press q to exit.

---

## 📷 Example Output

### INPUT IMAGE

<img width="683" height="402" alt="image" src="https://github.com/user-attachments/assets/c3d87217-cd54-499d-85fb-45c59baaed09" />

### OUTPUT IMAGE (FACE DETECTION)



✅ Face box drawn around the detected face.

🟢 User name and confidence score displayed.

❌ "Unknown" shown for untrained faces.

---

## 📚 Technologies Used

Python

OpenCV

Haar Cascades

LBPH (Local Binary Patterns Histograms)

---

## 🙌 Author

## Pari Gupta
### CodSoft Artificial Intelligence Internship – July 2025
GitHub
