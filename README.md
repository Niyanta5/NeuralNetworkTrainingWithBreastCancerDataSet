# Neural Network Implementation from Scratch for Breast Cancer Classification

![Neural Network](https://img.shields.io/badge/Neural%20Network-From%20Scratch-blue)
![Python](https://img.shields.io/badge/Python-3.7+-brightgreen)
![NumPy](https://img.shields.io/badge/NumPy-1.19+-orange)
![Breast Cancer Dataset](https://img.shields.io/badge/Dataset-Breast%20Cancer-pink)
![Accuracy](https://img.shields.io/badge/Test%20Accuracy-98.25%25-success)

## Project Overview

This repository contains a complete implementation of neural networks from scratch using only NumPy. The project progresses from fundamental building blocks to a sophisticated model for breast cancer classification, achieving **98.25%** accuracy on the test dataset.

## Key Features

- **Pure NumPy Implementation**: No deep learning frameworks - built entirely from mathematical first principles
- **Educational Progression**: Starts with simple concepts and builds to complex models
- **Visual Explanations**: Includes 2D and 3D visualizations of neural transformations
- **Advanced Techniques**: Implements regularization, dropout, and early stopping
- **Real-world Application**: Applied to breast cancer classification with clinical-grade accuracy

## Technical Implementation

The project is structured as a progressive journey through neural network concepts:

### 1. Basic Building Blocks
- Implementation of single neuron with sigmoid activation
- Gradient descent optimization from first principles
- Logical operations (AND gate) learned through training

### 2. Network Architecture Evolution
- Demonstration of linear separability limitations
- XOR problem visualization and solution through hidden layers
- 3D visualization of how neural networks transform feature spaces

### 3. Advanced Deep Learning Techniques
- L2 regularization to prevent overfitting
- Dropout implementation for improved generalization
- Early stopping mechanism based on validation performance
- Proper data standardization and train/validation/test splits

### 4. Breast Cancer Classification
- Feature extraction and standardization
- Hyperparameter optimization
- Performance evaluation metrics
- Sample prediction analysis

## Results

| Model | Training Accuracy | Test Accuracy | Early Stopping | Features |
|-------|------------------|--------------|---------------|----------|
| Simple Neural Network | 99.56% | 98.25% | No | Simple backpropagation |
| Enhanced Neural Network | 98.63% | 96.49% | Yes (Epoch 80) | L2 reg + Dropout |

## Code Structure

```
neural_network_from_scratch/
├── building_neural_networks.ipynb     # Main notebook with all implementations
├── README.md                          # This file
└── requirements.txt                   # Project dependencies
```

## Key Visualizations

The project includes critical visualizations that demonstrate:

1. Decision boundaries for logical operations
2. 3D transformation of the XOR problem space
3. Learning curves showing training and validation loss
4. How the model separates malignant vs. benign samples

## Installation and Usage

```bash
# Clone this repository
git clone https://github.com/Niyanta5/NeuralNetworkTrainingWithBreastCancerDataSet.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook building_neural_networks.ipynb
```

## Why This Matters

Understanding neural networks at this fundamental level provides several advantages:

- **Deep Understanding**: Building from scratch reveals the mathematics behind deep learning
- **Optimization Insight**: Shows exactly how weights update and how learning occurs
- **Debugging Capability**: Enables troubleshooting at every step of the network
- **Performance Control**: Allows fine-tuning of every aspect of the model

## Future Work

- Implementation of different activation functions (ReLU, Tanh)
- Adding convolutional layers for image-based diagnostics
- Extending to multi-class classification problems
- Implementing batch normalization and adaptive learning rates

## References

- Bishop, C. M. (2006). Pattern Recognition and Machine Learning.
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning.
- Sklearn's breast cancer dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

## Contact

For questions or collaboration opportunities, please reach out at [your-email@example.com](mailto:your-email@example.com).

---

*This project was developed to demonstrate advanced machine learning capabilities and deep understanding of neural network principles from first principles.*
