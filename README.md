# 👁️ Computer Vision Face Detection and Recognition System

A Python-based application utilizing OpenCV and deep learning techniques to perform real-time face detection and recognition. This project demonstrates the implementation of computer vision algorithms to identify and verify individuals from live video feeds or static images.

---

![OpenCV](https://img.shields.io/badge/Built%20With-OpenCV-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

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

Follow these steps to run the project via the provided Jupyter Notebook.

### 💻 Prerequisites

- **Python 3.x**
- **Jupyter Notebook** (Install: `pip install notebook`)
- Required libraries: OpenCV, TensorFlow, Keras, Pillow
  ```bash
  pip install opencv-python tensorflow keras pillow
  ```

### 📦 Step 1: Download the Project

Clone the repository or download the ZIP file and extract it.

### 📸 Step 2: Prepare the Data Directory

Before running notebook cells, organize your data directory as follows:

```
data/
├── Alice/
│   ├── 1.jpg
│   └── 2.jpg
└── Bob/
    ├── 1.jpg
    └── 2.jpg
```

- Each folder (`Alice`, `Bob`, etc.) should contain clear, front-facing images (2–5 images per person).

---

### 🚀 Step 3: Run the Jupyter Notebook

1. Open your terminal and navigate to the project directory.
2. Launch Jupyter Notebook:
```bash
jupyter notebook
```
3. In your browser, open the notebook file (`faceDetection.ipynb`) and run cells sequentially.

---

### 🧯 Troubleshooting

- **Module Not Found?** Ensure you've installed dependencies:
```bash
pip install opencv-python tensorflow keras pillow notebook
```
- **Notebook not opening?** Ensure Jupyter is correctly installed and running.

---

## 🙌 Acknowledgments

- **OpenCV** – For providing an incredibly powerful open-source computer vision library.
- **TensorFlow & Keras** – For simplifying deep learning model development and training.
- **Stack Overflow & GitHub Community** – For helpful discussions and code references during development.
- **Tutorial Authors & Online Resources** – For inspiration and foundational guidance in face recognition techniques.
- **Everyone Testing the System** – For helping refine the interface and improve accuracy with real-world feedback.
