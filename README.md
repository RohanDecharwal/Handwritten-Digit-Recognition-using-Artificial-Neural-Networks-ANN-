# Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## Student Details

| Field | Details |
|-------|---------|
| **Name** | Rohan Ramdhan Decharwal |
| **Batch** | AI/ML Internship – Batch 1(A) |
| **Mentor** | Nishant Shrivastava |
| **University** | VIT Bhopal University |
| **Course** | B.Tech Computer Science and Engineering (AI & ML) |

---

## Objective

The objective of this project is to develop an **Artificial Neural Network (ANN)** capable of recognizing handwritten digits (0–9) using the **MNIST Handwritten Digits Dataset**. The model is trained to classify grayscale images of handwritten digits with high accuracy using **TensorFlow/Keras**. This project demonstrates the application of deep learning techniques for image classification.

---

## Dataset

**MNIST Handwritten Digits Dataset**

**Kaggle Dataset:**  
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

> **Note:** The dataset is not included in this repository. Please download it from the Kaggle link above.

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Methodology

The project was completed using the following steps:

1. Loaded the MNIST dataset using Pandas.
2. Explored the dataset and displayed sample handwritten digit images.
3. Checked for missing values.
4. Separated input features and target labels.
5. Normalized pixel values to the range of **0–1**.
6. Applied **One-Hot Encoding** to the target labels.
7. Split the dataset into **80% training** and **20% testing** sets.
8. Built an **Artificial Neural Network (ANN)** with two hidden layers.
9. Compiled the model using the **Adam** optimizer and **Categorical Crossentropy** loss function.
10. Trained the model for **10 epochs**.
11. Evaluated the model using:
    - Test Accuracy
    - Confusion Matrix
    - Classification Report
12. Visualized model performance using:
    - Accuracy vs Epoch
    - Loss vs Epoch

---

## Model Architecture

| Layer | Configuration |
|--------|---------------|
| Input Layer | 784 Input Features |
| Hidden Layer 1 | 128 Neurons (ReLU) |
| Hidden Layer 2 | 64 Neurons (ReLU) |
| Output Layer | 10 Neurons (Softmax) |

**Optimizer:** Adam

**Loss Function:** Categorical Crossentropy

**Evaluation Metric:** Accuracy

**Epochs:** 10

---

## Results

The Artificial Neural Network successfully learned to recognize handwritten digits from the MNIST dataset. The model achieved high classification accuracy on the test dataset after training for 10 epochs. The confusion matrix indicated that most handwritten digits were correctly classified, while the accuracy and loss graphs demonstrated effective learning and good model convergence.

---

## Conclusion

This project demonstrates the effectiveness of Artificial Neural Networks for handwritten digit recognition. By preprocessing the image data and training a multi-layer neural network, the model successfully learned complex patterns from handwritten digit images and achieved high classification accuracy. Deep learning models automatically extract relevant features from image data, making them highly effective for image classification tasks compared to traditional machine learning algorithms. However, ANN models require greater computational resources and careful tuning to prevent overfitting. Overall, the developed ANN provides an accurate and reliable solution for handwritten digit recognition using the MNIST dataset.

---

## Repository Structure

```
Handwritten Digit Recognition using Artificial Neural Networks (ANN)/
│── Handwritten Digit Recognition using Artificial Neural Networks (ANN).ipynb
│── README.md
└── requirements.txt
```

---

## How to Run

1. Clone this repository.
2. Download the **MNIST Handwritten Digits Dataset** from Kaggle.
3. Place `mnist_train.csv` (and `mnist_test.csv`, if used) in the project directory.
4. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

5. Open `Assignment_8.ipynb` in **Google Colab**, **Jupyter Notebook**, or **VS Code**.
6. Run all the notebook cells sequentially.

---

## Author

**Rohan Ramdhan Decharwal**

**AI/ML Internship – Batch 1(A)**

**Mentor:** Nishant Shrivastava
