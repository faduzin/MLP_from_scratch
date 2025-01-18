# MLP From Scratch

This repository contains a project where a Multi-Layer Perceptron (MLP) is implemented from scratch without the use of libraries for creating the model. Instead, only core libraries like `pandas`, `numpy`, and `sklearn` are used for auxiliary tasks such as data handling, normalization, and evaluation.

## Repository Structure

```
.
├── notebook/
│   └── mlp-from-scratch.ipynb       # Jupyter Notebook with the MLP implementation
├── images/
│   ├── linear.png                   # Loss graph using the Linear activation function
│   ├── relu.png                     # Loss graph using the ReLU activation function
│   ├── sigmoid.png                  # Loss graph using the Sigmoid activation function
│   ├── softmax.png                  # Loss graph using the Softmax activation function
│   └── tanh.png                     # Loss graph using the Tanh activation function
├── datasets/
│   ├── iris.csv                     # Iris dataset (classification task)
│   └── housing.csv                  # Housing dataset (regression task)
└── README.md                        # Project documentation
```

## Features

- **Fully implemented MLP from scratch:**
  - No pre-built neural network libraries were used.
  - Forward propagation, backward propagation, and gradient updates implemented manually.

- **Visualization of loss trends:**
  - Loss graphs for different activation functions (`Linear`, `ReLU`, `Sigmoid`, `Softmax`, `Tanh`) available in the `images` folder.

- **Support for different tasks:**
  - Classification using the Iris dataset.
  - Regression using the Housing dataset.

## Requirements

The implementation relies on the following Python libraries:

- `numpy`: For vector and matrix operations.
- `pandas`: For data manipulation and loading.
- `scikit-learn`: For data normalization, splitting, and score evaluation.

Install the required libraries using:
```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mlp-from-scratch.git
   ```

2. Navigate to the `notebook` folder and open the Jupyter Notebook:
   ```bash
   cd notebook
   jupyter notebook mlp-from-scratch.ipynb
   ```

3. Follow the steps in the notebook to:
   - Load the datasets.
   - Train the MLP on the Iris and Housing datasets.
   - Visualize loss trends for different activation functions.

## Datasets

- **Iris dataset:** A classic dataset for classification tasks, containing measurements of iris flowers.
- **Housing dataset:** A dataset for regression tasks, predicting house prices based on various features.

Both datasets are available in the `datasets` folder in CSV format.

## Results

Loss graphs for each activation function are available in the `images` folder. Below are the highlights:

- **Linear:** Suitable for regression tasks but struggles with non-linear relationships.
- **ReLU:** Handles vanishing gradient issues but may face dead neurons.
- **Sigmoid:** Common for binary classification but prone to vanishing gradients.
- **Softmax:** Ideal for multi-class classification.
- **Tanh:** Works well for non-linear relationships, centered around zero.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The datasets are standard benchmark datasets for machine learning.
- Libraries used: `numpy`, `pandas`, and `scikit-learn`.

## Contributing

Feel free to open issues or create pull requests if you have suggestions or improvements!
