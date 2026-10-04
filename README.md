# Deep Learning for CC

A collection of my machine learning and deep learning lab implementations while learning the fundamentals.

## Contents

- Lab 1: Neural network from scratch using NumPy
- Lab 2: House price regression using PyTorch
- Lab 3: Iris classification using k-nearest neighbors
- Lab 4: ReLU and Leaky ReLU comparison
- Lab 5: ReLU and ELU comparison
- Lab 6: Customer category classification using k-nearest neighbors
- Lab 7: Customer clustering using K-Means and PCA
- Lab 8: Weather prediction using LSTM and GRU networks

## Datasets

The datasets used by the labs are stored in their respective `dataset` folders.

- `HousingData.csv` is used for house price regression in Labs 2, 4 and 5.
- `Mall_Customers.csv` is used for customer classification in Lab 6.
- `Unlabelled_dataset.csv` is used for clustering in Lab 7.
- `weather_prediction_dataset.csv` is used for weather prediction in Lab 8.
- Lab 1 uses a small dataset defined directly in the notebook.
- Lab 3 uses the Iris dataset from scikit-learn.

## Setup

Install the required packages:

```bash
pip install numpy pandas matplotlib scikit-learn torch tqdm kneed
```

Open any `main.ipynb` file in Jupyter Notebook or VS Code and run the cells in order.

The notebooks use relative dataset paths, so they should be run with the corresponding lab folder as the working directory.

## Goal

The purpose of this repository is to understand how machine learning and deep learning models work through implementation, experimentation, and comparison.

The notebooks include forward propagation, backpropagation, gradient descent, activation functions, loss functions, model training, evaluation metrics, clustering, and recurrent neural networks.

---

Built for learning, experimentation, and curiosity.
