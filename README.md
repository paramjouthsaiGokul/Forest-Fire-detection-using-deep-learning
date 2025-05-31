
# 🌲 Forest Fire Detection Using Deep Learning 🔥

## Overview

This project is a deep learning-based solution designed to detect forest fires using image classification techniques. Developed during a 4-week virtual internship under AICTE, Edunet Foundation, and Shell, the system leverages Convolutional Neural Networks (CNNs) to identify "Fire" and "No Fire" conditions in forest surveillance images. The primary goal is to enable early detection and alerting to prevent large-scale environmental and economic damage caused by wildfires.

Forest fires lead to biodiversity loss, air pollution, and economic setbacks. Traditional fire detection methods are often delayed or inaccurate. Our model aims to provide a real-time, AI-driven detection mechanism that enhances firefighting response times and promotes sustainable forest management.

---

## 🔧 Features

- 🔥 Detects fire and no-fire scenarios in images
- 📊 Achieves over 80% accuracy on test datasets
- 🧠 Built using Convolutional Neural Networks (CNN)
- 📷 Supports satellite, drone, and ground surveillance images
- 📱 Real-time alert system support (future integration)
- 🌍 Scalable for various regions and climates

---

## 🛠 Tech Stack

- **Programming Language**: Python  
- **Frameworks**: TensorFlow, Keras  
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib  
- **Environment**: Google Colab  
- **Dataset**: Kaggle – Fire and No Fire image dataset

---

## 📁 Dataset

- The dataset used is sourced from Kaggle and contains labeled images classified into two categories:
  - Fire
  - No Fire
- It includes forest visuals under different lighting, weather, and geographical conditions.

[🔗 Kaggle Dataset](https://www.kaggle.com/datasets)

---

## 🧠 Model Architecture

- The model is based on a **Convolutional Neural Network (CNN)**.
- Layers used: Conv2D, MaxPooling2D, Flatten, Dense
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy

---

## 🚀 Installation Instructions

```bash
# 1. Clone the repository
git clone https://github.com/paramjouthsaiGokul/Forest-Fire-detection-using-deep-learning.git
cd Forest-Fire-detection-using-deep-learning

# 2. (Optional) Create and activate a virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# 3. Install required dependencies
pip install -r requirements.txt

# 4. Run the Jupyter Notebook or Google Colab
