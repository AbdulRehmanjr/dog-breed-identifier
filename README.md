# Dog Breed Identification

Welcome to the **Dog Breed Identification App**, a deep learning-powered web application built with **TensorFlow**, **Keras**, and **Flask**. Designed for image classification, this project aims to accurately detect and identify **120 dog breeds** from raw images using a Convolutional Neural Network (CNN) trained on the official Kaggle dataset.

---

## 🚀 Project Overview

The Dog Breed Identifier is a machine learning model trained via **supervised learning** on a labeled dataset of over 10,000 images spanning **120 distinct dog breeds**. It extracts unique breed-specific features through a convolutional architecture and predicts the breed of dogs in unseen images. The final result is served via an intuitive web interface powered by Flask.

### ✨ Features

- **120 Dog Breeds Supported** – Covers a wide range of common and rare dog breeds  
- **Real Image Input** – Upload an image of any dog to get breed predictions  
- **Deep CNN Model** – Built using TensorFlow and Keras with high accuracy  
- **Interactive Flask Web App** – Easy-to-use interface for predictions  
- **Kaggle Dataset Integration** – Based on the official [Kaggle competition](https://www.kaggle.com/competitions/dog-breed-identification)  
- **Model Performance Reporting** – Shows breed confidence score

---

## 🛠️ Tech Stack

| Component       | Details                                                |
|-----------------|--------------------------------------------------------|
| Language        | Python                                                 |
| Framework       | Flask                                                  |
| ML Libraries    | TensorFlow, Keras, NumPy, Pandas                       |
| Model Type      | Convolutional Neural Network (CNN)                     |
| Dataset         | [Kaggle Dog Breed Identification](https://www.kaggle.com/competitions/dog-breed-identification/data) |
| Deployment      | Localhost via `flask run`                              |

---

## 📷 UI Screenshots

### 🐶 Homepage  
<img src="./screenshots/home-screenshot-classifier.png" alt="app screenshot" width="600"/>

### 📸 Prediction Result  
<img src="./screenshots/prediction-screenshot-classifier.png" alt="app screenshot" width="600"/>

---

## 📦 How to Run

### ✅ Requirements

- Python 3.8+
- Virtual environment tools (venv/pipenv)
- All required packages in `requirements.txt`

### 🔧 Setup Instructions

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/abdulrehmandev/dog-breed-classifier.git
   cd dog-breed-classifier
   ```

2. **Create & Activate Virtual Environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the App**  
   ```bash
   flask run
   ```

> 💡 *Make sure to download the dataset separately from [Kaggle](https://www.kaggle.com/competitions/dog-breed-identification/data) and place it in the appropriate directory before training or prediction.*

> 📝 You can also take model training *Notebook* from [Kaggle](https://www.kaggle.com/code/abdulrehmandev/dog-breed-identification)

---

## 🧠 Educational Purpose

This project was built to reinforce deep learning fundamentals such as:

- Image classification using CNNs  
- Data preprocessing and augmentation  
- Model evaluation and fine-tuning  
- Serving ML models through web applications

Perfect for ML beginners interested in combining computer vision and deployment.

---

#### Discoverability  
Dog Breed Classifier, TensorFlow CNN Projects, Image Recognition Flask App, Deep Learning Dog Image Classifier, Kaggle Dog Breed Challenge, Breed Identification AI, Python Image Classifier, Computer Vision Projects with Flask.

---

## 🤝 Contribution

Contributions, feature requests, or ideas are welcome! Fork the repo, create a branch, and submit a pull request. Let’s improve this together.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

[**Abdul Rehman**](https://abdulr.dev)

---
