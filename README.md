# CodeAlpha_HandwrittenCharacterRecognition
CodeAlpha Machine Learning Internship - Task 3 Handwritten Character Recognition

# Handwritten Character Recognition

## 📌 Project Overview

This project was developed as **Task 3 of my CodeAlpha Machine Learning Internship**.

The objective of this project is to build a machine learning model using a **Convolutional Neural Network (CNN)** to recognize handwritten digits from image data.

The project follows a complete machine learning workflow including data understanding, data preprocessing, exploratory data analysis, model building, model training, evaluation, and handwritten digit prediction.

---

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

The dataset contains grayscale images of handwritten digits from **0 to 9**.

Important characteristics include:

* Image Size: 28 × 28 pixels
* Number of Classes: 10
* Classes: 0–9
* Training Dataset: MNIST training data
* Testing Dataset: MNIST testing data

### Target Variable

`label`

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Loaded the MNIST dataset.
* Checked the dataset structure and information.
* Checked for missing values.
* Separated features and target labels.
* Checked the available digit classes.
* Normalized pixel values.
* Reshaped the images for CNN input.
* Prepared the data for model training and testing.

Pixel values were normalized to a range between **0 and 1**.

---

## 📈 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the handwritten digit dataset.

The project includes visualizations such as:

* Sample handwritten digit images
* Multiple digit samples
* Digit class distribution
* Training accuracy graph
* Validation accuracy graph
* Training loss graph
* Validation loss graph

These visualizations helped understand the dataset and monitor the model training process.

---

## ⚙️ Model Architecture

A **Convolutional Neural Network (CNN)** was developed for handwritten digit recognition.

The CNN model contains:

* Convolutional layers
* Max Pooling layers
* Flatten layer
* Dense layer
* Dropout layer
* Output layer with 10 classes

The output layer represents the ten digit classes from **0 to 9**.

---

## 🤖 Model Training

The CNN model was trained using the training dataset.

The model uses:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Evaluation Metric:** Accuracy
* **Validation:** Validation split during training

The training process was used to learn patterns from handwritten digit images.

---

## 📊 Model Results

The model was evaluated using the test dataset.

The project generates:

* Test Accuracy
* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Confusion Matrix
* Classification Report

The numerical results shown in the project are based on the actual execution of the notebook.

---

## 📉 Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

These metrics were used to evaluate the performance of the handwritten digit recognition model.

---

## 🔢 Digit Prediction

The trained CNN model was used to predict individual handwritten digit images.

The model takes a **28 × 28 pixel image** as input and predicts one of the ten digit classes from **0 to 9**.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow
* Keras
* Convolutional Neural Network (CNN)

---

## 📁 Project Structure

```text
CodeAlpha_HandwrittenCharacterRecognition/
│
├── CodeAlpha_Task3_Handwritten_Digit_Recognition.ipynb
├── mnist_train.csv
├── mnist_test.csv
└── README.md
```

---

## 🎯 Conclusion

This project demonstrates the use of a **Convolutional Neural Network for handwritten digit recognition**.

The model learns patterns from handwritten digit images and predicts the corresponding digit from 0 to 9.

The project provides practical experience in image preprocessing, CNN model development, model training, evaluation, and prediction.

---

## 🏢 Internship

**CodeAlpha Machine Learning Internship**

**Task 3 — Handwritten Character Recognition**

## 👩‍💻 Author

**Rahi Prajapati**

