# 📸 Face Recognition System v1.0

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-4.12+-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/License-MIT-41AD48?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <strong>A professional-grade, real-time biometric identification system.</strong><br>
  Built with performance and user experience in mind, featuring advanced HOG algorithms and a sleek dark-mode GUI.
</p>

---

## 🚀 Overview

The **Face Recognition System** is a modular Python-based application that leverages deep learning to identify faces in real-time. Whether you are managing security, tracking attendance, or exploring computer vision, this system provides the tools to log, analyze, and manage identities seamlessly.



### 💎 Key Highlights
* **Intelligent Detection:** Powered by Histogram of Oriented Gradients (HOG) for rapid processing.
* **Confidence Logic:** Dynamic color-coded visual feedback (🟢 High, 🟡 Medium, 🔴 Low).
* **Persistence:** Built-in SQLite integration to maintain a history of every identification event.
* **Optimized Engine:** Multi-frame skipping and performance-focused threading for high-FPS feeds.

---

## 🛠 Tech Stack & Architecture

| Category | Technology | Usage |
| :--- | :--- | :--- |
| **Language** | `Python 3.10+` | Core Logic & Scripting |
| **CV Engine** | `OpenCV` | Image transformation & Video I/O |
| **Deep Learning** | `Dlib / Face_Recognition` | 128D Face Embeddings |
| **UI Framework** | `Tkinter` | Modern Dark-Mode GUI |
| **Data Science** | `Pandas / NumPy` | Recognition analytics & History |
| **Database** | `SQLite3` | Persistent storage & logs |

---

## 📸 Interface Showcase

### 💠 The Desktop App
* **Real-time Feed:** Ultra-low latency video stream with detection overlays.
* **Identity Management:** Add or remove known faces via webcam or file upload.
* **History Logs:** Filterable database view showing who was seen and when.



---

## ⚙️ Installation

### ⚡ The Fast Way (Windows)
```bash
# Clone the repository
git clone [https://github.com/AmiNilay/face-recognition-system-version-control.git](https://github.com/AmiNilay/face-recognition-system-version-control.git)
cd face-recognition-system-version-control

# Automatic Setup
./INSTALL.bat
