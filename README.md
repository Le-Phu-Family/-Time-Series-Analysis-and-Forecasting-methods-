# Time Series Analysis and Forecasting Methods

> **Status:** 🚧 Đang thực hiện (Work in Progress)

## Project Introduction

This repository contains a collection of Jupyter Notebooks and datasets focused on **Time Series Analysis and Forecasting**. It serves as a comprehensive guide and practical workspace for exploring various time series concepts, ranging from basic graphics and data manipulation to advanced decomposition and feature extraction methods. The project utilizes popular Python libraries such as `pandas`, `statsforecast`, and `fpppy` (Forecasting: Principles and Practice for Python) to demonstrate these concepts.

## Project Structure

The repository is organized as follows:

```text
.
├── data/               # Contains various datasets (CSV, Excel) used across the notebooks
├── notebooks/          # Jupyter Notebooks organized by topics/chapters
│   ├── Chapter 1 - getting started.ipynb
│   ├── Chapter 2 - Time Series Graphics/
│   ├── Chapter 3 - Time Series Decomposition/
│   └── Chapter 4 - Times Series Features/
├── requirements.txt    # List of Python dependencies required to run the project
└── README.md           # Project documentation (this file)
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

Navigate to the `notebooks/` directory and open any chapter to start exploring the time series methods!