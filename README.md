# Plasma Machine Learning Library

Welcome to the **Plasma Machine Learning Library**, a comprehensive collection of models and tools designed to streamline your machine learning projects. This library includes a variety of models ranging from simple regression to advanced image generation, as well as essential utilities for data preprocessing.

## Available Models

### 1. SimpleLinearRegression
A straightforward model for performing linear regression. Ideal for quick and easy predictive analysis on numerical data.

### Sequential Models

#### 1. CSV_Descision_Model
- **Description**: A model specifically designed for predicting the next token or number in a sequence.
- **Output**: Predicts float values.
- **Requirements**: Must be fitted with a CSV file. Other data types are not supported for this model.

#### 2. PLASMA_LSTM
An advanced Long Short-Term Memory (LSTM) model for sequential data prediction, capable of handling complex patterns in time series data.

### Image Generating Models

#### 1. Image_Generating_Model
A general-purpose model for generating images based on input parameters. Suitable for a wide range of creative and practical applications.

#### 2. Diffusion_Model
An image generation model utilizing diffusion processes to create high-quality, realistic images.

#### 3. GAN_Model
A Generative Adversarial Network (GAN) model designed for generating highly realistic images by pitting two neural networks against each other in a game-theoretic setup.

## Machine Learning Related Classes

### 1. Tokenizer
A utility class for converting text into tokens. It supports two levels of tokenization:
- **Word Level**: Breaks down text into individual words.
- **Char Level**: Breaks down text into individual characters.

## Usage

To use the models and classes provided by the Plasma Machine Learning Library, simply import the desired model or class into your Python project. Ensure that you have the necessary dependencies installed and follow the model-specific requirements for fitting and prediction.

## Installation

To install the Plasma Machine Learning Library, you can use pip:

```bash
pip install plasma-ml
```

## Getting Started

Here’s a quick example of how to use the `SimpleLinearRegression` model:

```python
from plasma_ml import SimpleLinearRegression

# Initialize the model
model = SimpleLinearRegression()

# Fit the model with your data
model.fit(X_train, y_train)

# Make predictions
predictions = model.predict(X_test)
```

For more detailed documentation and examples, please refer to the individual model and class documentation.

## Contributing

We welcome contributions to the Plasma Machine Learning Library. If you have ideas for new features or improvements, please feel free to open an issue or submit a pull request on our GitHub repository.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or support, please contact our team at [support@plasma-ml.com](mailto:support@plasma-ml.com).

---

Thank you for using the Plasma Machine Learning Library! We hope it helps you achieve your machine learning goals efficiently and effectively.
