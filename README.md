# Time Series Analysis and Forecasting Methods

> **Status:** 🚧 Đang thực hiện (Work in Progress)

## Project Introduction

This repository contains a collection of Jupyter Notebooks and datasets focused on **Time Series Analysis and Forecasting**. It serves as a comprehensive guide and practical workspace for exploring various time series concepts, ranging from basic graphics and data manipulation to advanced decomposition and feature extraction methods. The project utilizes popular Python libraries such as `pandas`, `statsforecast`, and `fpppy` (Forecasting: Principles and Practice for Python) to demonstrate these concepts.

## Reference

This project is used for studying and practicing concepts from the following book:

Hyndman, R.J., Athanasopoulos, G., Garza, A., Challu, C., Mergenthaler, M., & Olivares, K.G. (2026). *Forecasting: Principles and Practice, the Pythonic Way*. OTexts: Melbourne, Australia. Available at: [OTexts.com/fpppy](https://otexts.com/fpppy). Accessed on 15 June 2026.

## Project Structure

The repository is organized as follows:

```text
.
├── data/                         # Datasets used across the notebooks (CSV and Excel files)
├── notebooks/                    # Jupyter notebooks organized by chapter
│   ├── Chapter 1 - getting started.ipynb
│   ├── Chapter 2 - Time Series Graphics/
│   │   ├── Chapter 2 - Time series graphics.ipynb
│   │   └── Exercises for Chapter 2.ipynb
│   ├── Chapter 3 - Time Series Decomposition/
│   │   ├── Chapter 3 - Time Series Decomposition.ipynb
│   │   └── Exercises for Chapter 3.ipynb
│   ├── Chapter 4 - Times Series Features/
│   │   ├── Chapter 4 - Time Series Features.ipynb
│   │   └── Exercises for Chapter 4.ipynb
│   ├── Chapter 5 - The forecaster’s toolbox/
│   │   ├── Chapter 5 - The forecaster’s toolbox.ipynb
│   │   └── Exercises for Chapter 5.ipynb
│   ├── Chapter 6 - Judgmental Forecasts/
│   │   └── Chapter 6 - Judgmental forecasts.ipynb
│   ├── Chapter 7 -  Time series regression models /
│   │   ├── Chapter 7 -  Time series regression models .ipynb
│   │   └── Exercises for Chapter 7.ipynb
│   ├── Chapter 8 -  Exponential smoothing/
│   │   ├── Chapter 8 -  Exponential smoothing.ipynb
│   │   └── Exercises for Chapter 8.ipynb
│   ├── Chapter 9 - ARIMA models/
│   │   ├── Chapter 9 - ARIMA models.ipynb
│   │   └── Exercises for Chapter 9.ipynb
│   ├── Chapter 12 - Advanced forecasting methods/
│   │   ├── Chapter 12 - Advanced forecasting methods.ipynb
│   │   └── Exercises for Chapter 12.ipynb
│   ├── Chapter 13 - Some practical forecasting issues /
│   │   ├── Chapter 13 - Some practical forecasting issues .ipynb
│   │   └── Exercises for Chapter 13.ipynb
│   └── _setup.py                 # Shared notebook setup/helpers
├── requirements.txt              # Python dependencies required to run the project
└── README.md                     # Project documentation
```

## Guide to Run This Project

Follow these steps to set up the environment and run the notebooks on your local machine:

### 1. Clone the repository

First, clone this repository to your local machine:
```bash
git clone https://github.com/Le-Phu-Family/-Time-Series-Analysis-and-Forecasting-methods-.git
cd -Time-Series-Analysis-and-Forecasting-methods-
```

### 2. Set up a virtual environment (Recommended)

It's highly recommended to use a virtual environment to manage your project dependencies and avoid conflicts.

**On Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install the required dependencies

Install the necessary Python packages listed in the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

Once the dependencies are installed, you can launch Jupyter Notebook or Jupyter Lab (or use an IDE like VSCode) to interact with the `.ipynb` files:

```bash
jupyter lab
```

Navigate to the `notebooks/` directory and open any chapter to start exploring the time series methods!
