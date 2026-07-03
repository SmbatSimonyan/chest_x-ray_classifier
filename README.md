# 🩻 Chest X-Ray Classifier

A deep learning-based medical image classification project that automatically classifies chest X-ray images into different diagnostic categories using Convolutional Neural Networks (CNNs) and TensorFlow/Keras.

The project demonstrates how deep learning can assist in computer-aided diagnosis by analyzing chest radiographs and predicting disease classes with high accuracy.

---

## 📌 Project Overview

Chest X-rays are among the most frequently used medical imaging techniques for diagnosing lung diseases. Manual interpretation requires significant expertise and can be time-consuming.

This project utilizes a Convolutional Neural Network (CNN) to classify chest X-ray images automatically, providing a fast and reliable prediction system.

---

## 🚀 Features

- Image preprocessing and normalization
- Data augmentation
- CNN-based image classification
- TensorFlow/Keras implementation
- Model training and validation
- Performance evaluation
- Prediction on unseen X-ray images
- Easy-to-use Jupyter Notebook

---

## 🗂 Dataset

The dataset consists of chest X-ray images organized into class folders.

Typical classes include:

- Normal
- Pneumonia

*(Depending on the dataset used in your notebook, additional classes may also be included.)*

---

## 🧠 Model Architecture

The project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

Typical architecture includes:

- Convolution Layers
- MaxPooling Layers
- Batch Normalization
- Dropout
- Fully Connected (Dense) Layers
- Softmax/Sigmoid Output Layer

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Chest_XRay_Classifier/
│
├── chest.ipynb
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── models/
├── images/
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/SmbatSimonyan/chest_x-ray_classifier.git
```

Move into the project

```bash
cd chest_x-ray_classifier
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
chest.ipynb
```

---

## ▶️ Training

Run all notebook cells to:

- Load dataset
- Preprocess images
- Train CNN
- Evaluate performance
- Save trained model

---

## 📈 Evaluation

The notebook evaluates the model using metrics such as:

- Accuracy
- Loss
- Validation Accuracy
- Validation Loss
- Prediction Results
- Confusion Matrix (if included)
- Classification Report (if included)

---

## 🔮 Future Improvements

- Transfer Learning (EfficientNet, ResNet50, DenseNet121)
- Hyperparameter tuning
- Model deployment with Flask/FastAPI
- Grad-CAM visualization
- Support for multiple lung diseases
- Web application interface

---

## 💻 Requirements

- Python 3.10+
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome.

Feel free to fork the repository and submit a Pull Request.

---

## 👨‍💻 Author

**Smbat Simonyan**

GitHub:
https://github.com/SmbatSimonyan

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
