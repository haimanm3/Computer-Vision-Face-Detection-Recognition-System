# 👁️ Computer Vision Face Detection and Recognition System

A Python-based application utilizing OpenCV and deep learning techniques to perform real-time face detection and recognition. This project demonstrates the implementation of computer vision algorithms to identify and verify individuals from live video feeds or static images.

---

![OpenCV](https://img.shields.io/badge/Built%20With-OpenCV-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/github/license/haimanm3/Computer-Vision-Face-Detection-Recognition-System)

---

## 🚀 Features

- 🎥 **Real-time Face Detection** – Using Haar cascades and deep models
- 🧠 **Face Recognition** – Verifies identities by comparing faces against a known database
- 🖼️ **Image and Video Support** – Works on static files and live webcam streams
- 🖱️ **Graphical Interface** – Tkinter-based UI for interaction
- 📁 **Scalable Face Database** – Organize new identities easily
- 🧩 **Modular Codebase** – Clean, organized Python scripts for detection, recognition, and GUI

---

## 🛠️ Technologies Used

| Component                | Technology                                      |
|--------------------------|-------------------------------------------------|
| Programming Language     | Python 3.x                                         |
| Computer Vision Library  | OpenCV                                          |
| Deep Learning Framework  | TensorFlow/Keras                                |
| GUI Framework            | Tkinter                                         |
| Data Storage             | Local filesystem (for images), SQLite (optional)                                          |
| Version Control        | Git & GitHub (if used for sharing) |

---

## ▶️ How to Use

Follow these steps to set up and run the application locally — GitHub is not required.

### 📥 Step 1: Download the Project

- Obtain the full project folder via ZIP, USB, or file sharing.
- Extract the folder and ensure the structure stays intact:

```
Computer-Vision-Face-Detection-Recognition-System/
├── data/
├── models/
├── src/
└── README.md
```

---

### 🐍 Step 2: Install Python

Ensure Python 3.x is installed on your machine.

To check:
```bash
python --version
```

If it is not installed, download it from:  
👉 https://www.python.org/downloads/

---

### 📦 Step 3: Install Required Libraries

Open a terminal or command prompt and run:

```bash
pip install opencv-python tensorflow keras pillow
```

---

### 📸 Step 4: Prepare Face Data

Inside the `data/` folder:

1. Create one folder for each person to be recognized.
2. Add 2–5 clear, front-facing images to each folder.

Example structure:

```
data/
├── Alice/
│   ├── 1.jpg
│   └── 2.jpg
└── Bob/
    ├── 1.jpg
    └── 2.jpg
```

---

### ▶️ Step 5: Run the Application

1. Open a terminal and navigate to the `src/` directory:

```bash
cd path/to/Computer-Vision-Face-Detection-Recognition-System/src
```

2. Launch the app:

```bash
python gui.py
```

The GUI will open and allow you to:

- Start live face detection using your webcam
- Recognize people from the image database
- Add or update face entries

---

### 🧯 Troubleshooting

- **Webcam Not Working?**  
  Ensure no other apps are using it, and your system has granted access.

- **Face Not Recognized?**  
  Use clearer, well-lit images. Add more examples per person.

- **Missing Modules?**  
  Reinstall required libraries:

  ```bash
  pip install opencv-python tensorflow keras pillow
  ```
---

## 🙌 Acknowledgments

- **OpenCV** – For providing an incredibly powerful open-source computer vision library.
- **TensorFlow & Keras** – For simplifying deep learning model development and training.
- **Stack Overflow & GitHub Community** – For helpful discussions and code references during development.
- **Tutorial Authors & Online Resources** – For inspiration and foundational guidance in face recognition techniques.
- **Everyone Testing the System** – For helping refine the interface and improve accuracy with real-world feedback.
