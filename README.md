<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

# TENNIS_ANALYSIS_SYSTEM

<em>Elevate Performance Through Intelligent Tennis Insights</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/amiliceviic/Tennis_Analysis_System?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/amiliceviic/Tennis_Analysis_System?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/amiliceviic/Tennis_Analysis_System?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">

</div>
<br>

---

## 📄 Table of Contents

- [Overview](#-overview)
- [Modules Used](#-modules-used)
- [Trained Models](#-trained-models)
- [Requirements](#-requirements)
- [Getting Started](#-getting-started)
    - [Prerequisites](#-prerequisites)
    - [Installation](#-installation)
    - [Usage](#-usage)

---

## ✨ Overview

This project focuses on the analysis of tennis players in video footage to evaluate their movement speed, shot speed, and shot count. It employs YOLO for real-time detection of players and the tennis ball, while convolutional neural networks (CNNs) are used to extract keypoints of the court. Designed as a practical, hands-on initiative, this project offers an excellent opportunity to enhance your expertise in machine learning and computer vision.

![Screenshot](output_videos/screenshot.png)

**Why Tennis_Analysis_System?**

This project aims to enhance player performance and coaching strategies through data-driven insights. The core features include:

- 🎾 **AI and Machine Learning Integration:** Utilize YOLO and PyTorch for advanced performance analysis.
- 📊 **Real-Time Object Tracking:** Track players and balls in video footage seamlessly.
- 📈 **Comprehensive Data Analysis:** Gain detailed statistics and visualizations of gameplay dynamics.
- 🛠️ **Custom Model Training:** Train specialized models for tennis ball detection and court keypoints.
- 🎥 **Utility Functions:** Access essential video processing tools for enhanced functionality.

---

## 🥡 Modules Used

The following modules are used in this project:
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

---

## 🕹️ Trained Models

* Trained YOLOV5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court key point model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing

---

## ♟️ Training

* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

---

## 🪁 Requirements

To run this project, you need to have the following requirements installed:
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv

---

## 🚀 Getting Started

### 📋 Prerequisites

This project requires the following dependencies:

- **Programming Language:** Python
- **Package Manager:** Conda

### ⚙️ Installation

Build Tennis_Analysis_System from the source and intsall dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/amiliceviic/Tennis_Analysis_System
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Tennis_Analysis_System
    ```

3. **Install the dependencies:**

**Using [conda](https://docs.conda.io/):**

```sh
❯ conda env create -f conda.yml
```

### 💻 Usage

Run the project with:

**Using [conda](https://docs.conda.io/):**

```sh
conda activate {venv}
python {entrypoint}
```

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
