# Deep Learning for Financial Time Series Prediction

## Overview

This project explores deep learning methods for financial time series prediction and portfolio-related forecasting tasks.

The work focuses on designing, training, and evaluating neural network architectures for sequential financial data, including recurrent and convolutional models. The project investigates how deep learning techniques can capture temporal patterns in financial markets and compares different architectures under a common experimental framework.

The repository contains my completed implementations, experiments, and analysis developed as part of graduate coursework.

---

## Academic Context

This project was completed as part of the graduate course:

**AI for Financial Engineering and Operations Research (AI for FE & OR)**
**Columbia University**

The assignment framework, helper utilities, and portions of the starter code were provided by the course staff.

The model implementations, experiments, hyperparameter tuning, analysis, and completed solutions contained in this repository are my own work.

---

## Project Components

The notebook explores several deep learning approaches for financial prediction, including:

* Feedforward Neural Networks
* Long Short-Term Memory (LSTM) Networks
* Convolutional Neural Networks (CNNs)
* Hyperparameter Optimization
* Model Comparison and Evaluation

The objective is to learn predictive patterns from historical financial data and evaluate the effectiveness of different neural network architectures.

---

## Methodology

### Data Processing

The workflow includes:

* Time-series preprocessing
* Feature construction
* Train / validation / test splitting
* Sequence generation for temporal models

### Deep Learning Models

The project evaluates multiple architectures:

#### Feedforward Neural Networks

Baseline fully connected networks for predictive modeling.

#### LSTM Networks

Recurrent neural networks designed to capture temporal dependencies in sequential financial data.

#### Convolutional Neural Networks

1D convolutional architectures that extract local temporal patterns from historical observations.

### Hyperparameter Optimization

The project includes model tuning and architecture selection to improve predictive performance.

---

## Technologies

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Optuna
* Yahoo Finance API (yfinance)

---

## Data Availability

The original synthetic datasets used in portions of the coursework are not included in this repository.

These datasets were provided as part of the course framework and are therefore not redistributed.

The final section of the project demonstrates the methodology using publicly available financial market data retrieved through Yahoo Finance.

---

## Missing Course Utilities

The original coursework included helper functions and utilities contained in a course-provided `library.py` file.

That file is not redistributed in this repository.

The repository is intended to showcase the implemented deep learning models, experiments, and analysis rather than provide a fully reproducible copy of the course framework.

---

## Repository Structure

```text
deep-learning-finance-time-series/
│
├── README.md
├── requirements.txt
├── DL_Finance.ipynb
```

---

## My Contribution

My work focused on:

* Neural network implementation
* LSTM and CNN model development
* Hyperparameter tuning
* Experimental evaluation
* Financial time-series analysis
* Model comparison and interpretation

---

## Notes

This repository is intended as a portfolio project demonstrating deep learning applications in financial engineering and time-series forecasting.

It does not redistribute course-provided datasets, helper libraries, or assignment materials.

