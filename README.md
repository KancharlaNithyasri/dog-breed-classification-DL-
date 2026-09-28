# 🐶 Dog Breed Classification using Deep Learning

A deep learning project for classifying dog images into **120 different dog breeds** using **TensorFlow, Keras, and EfficientNetB0 transfer learning**.

## 📌 Project Overview

This project uses the **Stanford Dogs Dataset**, containing **20,580 images across 120 dog breeds**.

The model was developed and trained using Google Colab with GPU acceleration.

## 📊 Dataset

* Total images: 20,580
* Dog breeds: 120
* Training images: 12,000
* Evaluation images: 8,580
* Image size: 224 × 224

## 🧠 Model

The project uses **EfficientNetB0 pretrained on ImageNet** as the base model.

The classification architecture includes:

* EfficientNetB0
* Global Average Pooling
* Dropout
* Dense layer with 120 output classes
* Softmax activation

## ⚙️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Google Colab
* EfficientNetB0
* Transfer Learning

## 📈 Results

| Metric              | Result |
| ------------------- | -----: |
| Training Accuracy   | 92.67% |
| Evaluation Accuracy | 85.93% |

The evaluation set was used as `validation_data` during the training workflow, so the 85.93% figure is reported as evaluation accuracy rather than as a completely untouched final test score.

## 🔍 Evaluation

The model was evaluated using:

* Accuracy and loss analysis
* Confusion matrix
* Per-class accuracy
* Misclassification analysis
* Top-5 predictions

## 🚀 Prediction

A custom image prediction pipeline was created to:

1. Upload a new dog image
2. Resize it to 224 × 224
3. Pass it through the trained model
4. Predict the dog breed
5. Display the prediction confidence
6. Display the top-5 predicted breeds

## 📓 Notebook

The complete implementation is available in:

`Dog_Breed_Classification.ipynb`

## 🛠️ How to Run

The notebook can be opened and executed using Google Colab.

The Stanford Dogs dataset needs to be downloaded separately because the dataset files are not included in this repository.

## 👩‍💻 Author

**Kancharla Nithyasri**

B.Tech Computer Science Engineering
Rajiv Gandhi University of Knowledge Technologies, Basar
