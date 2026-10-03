# Iris Classification using Perceptron and Artificial Neural Network

## Project Overview
This project classifies Iris flowers into three species using machine learning.

The notebook compares:
- A **Perceptron** classifier
- A **Artificial Neural Network (ANN)** built with TensorFlow/Keras

## Dataset
The project uses the classic Iris dataset with four input features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Workflow
1. Load and inspect the dataset
2. Explore the data with a pair plot
3. Separate features and target
4. Encode target labels
5. Split data into training and test sets
6. Standardize the features
7. Train a Perceptron
8. Evaluate the Perceptron
9. Build and train an ANN
10. Evaluate the ANN
11. Visualize training and validation accuracy

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

## How to Run

Install the required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

Then open the notebook:

```bash
jupyter notebook ANNproject_github.ipynb
```

Make sure `Iris.csv` is in the same folder as the notebook.

## Project Structure

```text
iris-ann-classification/
├── ANNproject_github.ipynb
├── Iris.csv
└── README.md
```

## What I Learned
This project helped me practice data preprocessing, train/test splitting, feature scaling, label encoding, classification, model evaluation, and building a basic neural network with Keras.
