# Assistive System for Blind People

### Money Counting and Obstacle Detection using Computer Vision

---

## Overview

The **Assistive System for Blind People** is an AI-based solution designed to improve the independence and safety of visually impaired individuals. The system addresses two key real-world challenges: **obstacle detection** and **currency recognition**, using computer vision and deep learning techniques.

---

## Problem Statement

Visually impaired individuals often face:

* Difficulty in detecting nearby obstacles while navigating
* Challenges in identifying and managing currency

This system aims to provide real-time assistance to overcome these limitations.

---

## Features

### 1. Obstacle Detection

* Real-time object detection using **YOLOv9**
* Depth estimation using **MiDaS**
* Identifies nearby obstacles and alerts the user
* Designed for real-time environmental awareness

---

### 2. Currency Recognition

* Custom-trained **ResNet50 model**
* Recognizes Indian currency denominations
* Provides audio feedback of detected currency value

---

### 3. Money Counter

* Accepts a target amount (e.g., ₹150)
* Detects available notes
* Assists in selecting the correct combination of currency

---

## Technology Stack

**Languages:**

* Python

**Frameworks & Tools:**

* Streamlit

**Libraries:**

* OpenCV
* NumPy
* PyTorch

**Models Used:**

* YOLOv9 (Object Detection)
* MiDaS (Depth Estimation)
* ResNet50 (Image Classification)

---

## Project Structure

```
assistive-system-for-blind-people/
│
├── obstacle_detection.py
├── currency_reader.py
├── money_counter.py
├── models/
├── utils/
├── data/
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/atharva481/assistive-system-for-blind-people.git
cd assistive-system-for-blind-people
```

### Create virtual environment

```bash
python -m venv .venv
source .venv/Scripts/activate   # Windows
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

### Run Obstacle Detection

```bash
streamlit run obstacle_detection.py
```

### Run Currency Recognition

```bash
streamlit run currency_reader.py
```

---

## Results

The system successfully:

* Detects objects in real-time using YOLOv9
* Estimates depth for obstacle awareness using MiDaS
* Identifies Indian currency denominations using a trained ResNet50 model

---

## Future Work

* Real-time voice navigation alerts
* Video-based continuous detection
* Mobile application deployment
* Improved model accuracy with larger datasets

---

## Contribution

Contributions are welcome. Please fork the repository and submit a pull request for any improvements.

---

## License

This project is licensed under the MIT License.

---

## Author

Atharva Sawant
