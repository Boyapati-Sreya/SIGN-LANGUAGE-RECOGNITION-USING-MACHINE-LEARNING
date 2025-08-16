# Sign Language Recognition using Machine Learning

This project focuses on building a **Sign Language Recognition (SLR)** system that bridges the communication gap between the deaf/mute and hearing communities. It leverages **Computer Vision** and **Deep Learning** to recognize sign language gestures and convert them into text in real-time.

## ✨ Features
- Real-time **hand gesture recognition** using OpenCV and CVzone.
- Model trained with **Convolutional Neural Networks (CNNs)** using TensorFlow/Keras.
- Supports recognition of **26 alphabets (A–Z)**.
- Custom dataset created for training (`Data/` folder).
- Modular code for **data collection**, **training**, and **testing**.

## 📂 Project Structure

## ⚙️ Requirements
- Python 3.9.5
- Libraries:
  - OpenCV
  - CVzone
  - NumPy
  - TensorFlow/Keras
  - Scikit-learn

Install dependencies:
```bash
pip install -r requirements.txt
git clone https://github.com/Boyapati-Sreya/SIGN-LANGUAGE-RECOGNITION-USING-MACHINE-LEARNING.git
cd SIGN-LANGUAGE-RECOGNITION-USING-MACHINE-LEARNING
python datacollection.py
python test.py
📊 Model Training

Dataset: Custom hand gesture images (Data/).

Model: CNN trained using Google Teachable Machine + TensorFlow.

Output: Predicts alphabetic gestures A–Z with high accuracy.

🔮 Future Scope

Improve accuracy using Transformer-based models.

Expand recognition to words and sentences.

Integrate with AR/VR for immersive communication.

Support speech output for recognized gestures.


🌟 Contribution

Feel free to fork this repo, create a new branch, and submit a pull request for improvements!
