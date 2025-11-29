# Invisibility-Cloak
A fun computer vision project inspired by the Harry Potter “Invisibility Cloak” effect. This project detects a specific color (or white cloth in Streamlit version) in the video feed and replaces it with the background—making the object appear invisible.

# 🧙‍♂️ Invisibility Cloak – OpenCV & Streamlit

A fun computer vision project inspired by the Harry Potter “Invisibility Cloak” effect.
This project detects a specific color (or white cloth in Streamlit version) in the video feed and replaces it with the background—making the object appear invisible.

This repository contains:

invisibility_cloak.py → Real-time invisibility effect using OpenCV

streamlit_app.py → Web-based invisibility demo using Streamlit

requirements.txt → Required Python dependencies

# 🧿 Invisibility Cloak (OpenCV Version)

A fully interactive, real-time invisibility cloak developed using OpenCV, HSV masking, and background segmentation.

# ✨ Features

Real-time webcam-based invisibility effect

Adjustable HSV sliders to detect specific colors

Presets for: Red, Blue, Green

Background capture with key [b]

Toggle HSV controls with [h]

Mirror mode for natural webcam behavior

# 🎮 Controls
Key	Action
b	Capture background
1	Use Red cloak preset
2	Use Blue cloak preset
3	Use Green cloak preset
h	Show/hide HSV sliders
q	Quit application
▶️ Run Locally
pip install -r requirements.txt
python invisibility_cloak.py

2️⃣ 🌐 Invisibility Cloak – Streamlit Version

A simplified photo-based implementation using the browser camera.

# 🎥 How It Works

Capture a background photo with an empty frame
Capture a second photo holding a white cloth
The white region gets replaced by the background → invisibility effect

# 🔍 Features

Browser-based, no manual HSV tuning
Detects white cloth using HSV threshold
Performs masking + replacement automatically
Displays final output inside the app
Option to reset the background

▶️ Run the Streamlit App
pip install -r requirements.txt
streamlit run streamlit_app.py

# 🧰 Requirements

Listed in requirements.txt

opencv-python
numpy

# 📂 Project Structure
.
├── invisibility_cloak.py     # Real-time OpenCV version
├── streamlit_app.py          # Streamlit-based web version
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation


# 🏆 Project Summary

This project demonstrates real-world use of:
✔ Computer Vision
✔ HSV masking
✔ Morphological operations
✔ Webcam frame processing
✔ Image blending
✔ Web-based CV deployment with Streamlit

Created By : Harsh Saxena
