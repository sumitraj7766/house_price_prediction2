# House Price Prediction Using PyTorch

A beginner-friendly machine learning project exploring house price prediction through neural networks using PyTorch.

## Project Overview

This project implements two machine learning tasks using synthetic housing data:

- **Regression:** Predict house prices from area, number of bedrooms, and house age.
- **Binary Classification:** Classify houses as affordable or expensive based on the median generated house price.

## Technologies Used

- Python
- PyTorch
- Matplotlib
- Google Colab

## Features

- Synthetic dataset generation
- Exploratory data visualization
- Training and testing split (80:20)
- Feature standardization
- Feedforward neural networks
- Regression using Mean Squared Error (MSE)
- Classification using Binary Cross-Entropy with logits
- Loss-curve visualization
- Actual versus predicted price comparison
- Evaluation using test MSE and RMSE

## Model Architecture

The neural network contains:

1. Input layer: 3 features
2. Hidden layer: 16 neurons with ReLU activation
3. Hidden layer: 8 neurons with ReLU activation
4. Output layer: 1 neuron

The regression model predicts a continuous house price. The classification model produces a logit that is converted to a probability using the sigmoid function.

## Dataset

The notebook generates 100 synthetic house samples with these features:

| Feature | Description |
|---|---|
| Area | House area in square feet |
| Bedrooms | Number of bedrooms |
| Age | House age in years |
| Price | Generated target price |

The synthetic price follows a predefined relationship with random noise. It is intended for educational experimentation and does not represent real-world market prices.

## Evaluation

The regression notebook reports test MSE and RMSE. The classification notebook examines predicted probabilities and class labels.

Results may vary if model initialization, training settings, or dataset generation changes.

## How to Run

1. Open `house_price_prediction.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Review the plots, predictions, and evaluation metrics.

## Limitations

- Uses a small synthetic dataset.
- Does not use real property-market data.
- Results are intended for learning, not real-world property valuation.

## Author

Sumit Kumar

## License

This project is available for educational purposes.
