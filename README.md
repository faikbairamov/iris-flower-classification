# Iris Flower Classification

This project implements a softmax classifier from scratch to classify iris flowers into three species: _Setosa_, _Versicolor_, and _Virginica_. The implementation is done in Python using only basic libraries and without any machine learning frameworks.

## Dataset

The dataset used is the [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains 150 samples with the following features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)
- Species (label)

The dataset is stored in `data/iris_data.csv`.

## Features

- Data normalization
- Manual one-hot encoding of labels
- Softmax function implementation
- Cross-entropy loss calculation
- Gradient descent optimization
- Accuracy evaluation on validation data

## Project Structure

- `iris_softmax_classification.ipynb`: Main Jupyter Notebook with code, comments, and visualizations
- `data/iris_data.csv`: Dataset file
- `README.md`: Project documentation

## Requirements

- Python 3.8 or higher
- NumPy
- Pandas
- Matplotlib
- scikit-learn (only for `train_test_split`)

To install the dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn

```

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/iris-softmax-classification.git
cd iris-softmax-classification
```

Ensure the dataset file `iris_data.csv` is located in the `data/` directory.

Launch the notebook:

```bash
jupyter notebook iris_softmax_classification.ipynb
```

Execute the cells in order to follow the preprocessing, model implementation, training, and evaluation steps.
