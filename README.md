# ✋🤖 Hand-Sign-Detection-using-Deep-Learning

**Hand-Sign-Detection-using-Deep-Learning** is a project designed to assist the deaf community by translating hand signs into alphabet letters. Using computer vision and deep learning, this system bridges communication gaps and enhances accessibility. 🧏‍♂️💡

---

## 🌟 Features
- 📷 **Real-Time Hand Detection**: Detects hands using `cvzone.HandTrackingModule`.
- 🖼️ **Image Preprocessing**: Captures, resizes, and adjusts aspect ratios for accurate recognition.
- 🧠 **Deep Learning Integration**: Utilizes a pre-trained Keras model to classify hand gestures into letters.
- 🔤 **Live Feedback**: Displays the detected letter directly on the video stream.

---

## 🚀 How It Works
1. **Data Collection**:
   - Use the `data_collection.py` script to capture hand gesture images and save them for training. 📸
2. **Real-Time Detection**:
   - The `test.py` script processes webcam input and identifies the corresponding letter for the detected hand sign. 🎥

---

## 📂 Project Structure
- **`data_collection.py`**: Script for collecting and preprocessing hand gesture images.
- **`test.py`**: Script for real-time prediction of hand signs using the deep learning model.
- **`model/`**: Directory containing the pre-trained `keras_model.h5` and `labels.txt`.

---

## 🛠️ Dependencies
- OpenCV 🎥
- cvzone ✨
- NumPy ➕
- TensorFlow/Keras 🧠

