# 🖐️ Sign Language Recognition System

## 📌 Project Overview

Today, individuals with hearing and speech impairments face significant challenges in communication. Since they are unable to interact effectively with people who do not understand sign language, they often encounter obstacles in social, educational, and professional environments. However, with the advancements in technology, many of these barriers can now be mitigated.

This project provides not only a technical solution but also a social contribution aimed at enhancing the active participation of hearing- and speech-impaired individuals in daily life. By detecting sign language gestures through a camera and converting them into text, the system aims to facilitate communication with people who do not know sign language. This work can be seen as an initial step toward addressing the communication barriers faced by these individuals.

---

## 🖼️ Project Visuals

<p float="left">
  <img src="images/image_1.jpeg" width="150" style="margin-right:10px; margin-bottom:10px" />
  <img src="images/image_2.jpeg" width="150" style="margin-right:10px; margin-bottom:10px" />
  <img src="images/image_3.jpeg" width="150" style="margin-right:10px; margin-bottom:10px" />
  </p>
  
---

## 🚀 Features

✔️ Real-time gesture detection

✔️ Clean OpenCV interface

✔️ A dataset of 12,591 images covering 48 different sign classes

✔️ Fully custom-created dataset

✔️ TensorFlow/Keras-based model

✔️ Easily implementable in other projects

---

## ⚙️ Installation & Setup

- Clone the repository
```bash
git clone https://github.com/OmerFarukArpa/sign-language-recognition-system
```
```bash
cd your-sign-language-project
```
- Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # Linux / macOS
venv\Scripts\activate     # Windows
```
- Install dependencies
```bash
pip install -r requirements.txt
```
- Run the application

---

## 📱 How It Works

- Start the project 
- Position yourself in front of the camera (both the person performing the sign and the person viewing the output)
- Perform the sign language gesture toward the camera
- The meaning of the gesture will be displayed on the screen as text, enabling communication between both individuals

---

## 🛠️ Technologies Used

- Python: The entire project is developed in Python due to its open-source nature, extensive library support, and its widespread use in the field of artificial intelligence.

- OpenCV: Used for real-time image processing tasks such as handling camera input, frame processing, hand gesture extraction, and preparing data for the model.

- TensorFlow & Keras: Employed to run the machine learning model. The project uses an .h5 model file fully compatible with Keras.

- NumPy: Utilized for mathematical operations, working with multi-dimensional arrays, and preparing input data for the model.

---

## 🖼️ Dataset Creation

A ready-made dataset was not used in this project; all images were created manually by me. This approach was chosen to enhance originality and improve real-world adaptability.

The Turkish Sign Language Dictionary served as the primary reference during dataset creation. Numerous images were captured in front of a camera under different angles and lighting conditions for letters and commonly used expressions. This ensured greater robustness against variations in users and environments.

In total, 48 classes were created:

- 22 sign language letters

- 24 commonly used expressions

- Total dataset size: 12,591 manually created images

---

## ⚖️ Data Balance

Care was taken to keep the number of images per class balanced. This prevented the model from becoming biased toward specific classes and significantly improved prediction accuracy.

It was observed that the model performed more stably and consistently when class imbalance was minimized.

---



