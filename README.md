Neural Network Models as an Alternative to the Black-Scholes Equation for Option Pricing

Project Description
This project explores the use of Multi-Layer Perceptrons (MLPs) to predict option prices, offering a data-driven alternative to the traditional Black-Scholes model. While Black-Scholes provides a closed-form solution for European options, it assumes ideal market conditions (e.g., constant volatility, no transaction costs) and struggles with real-world challenges like the volatility smile. In contrast, neural networks can learn complex, nonlinear pricing dynamics from historical data.

The project aims to compare the performance of MLP models and Black-Scholes using Mean Squared Error (MSE) and Mean Absolute Percentage Error (MAPE) as evaluation metrics.

Project Objectives

Implement Multi-Layer Perceptrons (MLPs) for option pricing.
Use Black-Scholes as a baseline for comparison.
Evaluate the models using real-world options data from OptionMetrics IvyDB EU.
Generate synthetic data if necessary to improve robustness.
Compare the results based on MSE and MAPE metrics.
Repository Structure
cmse492_project/
│
├── MLP/ # Scripts for defining and training MLP models.
│ ├── train_mlp.py # Main script to train the MLP model.
│ └── evaluate_mlp.py # Evaluates the performance of the MLP model.
│
├── black_scholes/ # Implementation of the Black-Scholes model.
│ └── black_scholes.py # Baseline option pricing script.
│
├── data_exploration/ # Notebooks for exploratory data analysis.
│ └── data_exploration.ipynb # Jupyter notebook for feature exploration.
│
├── datasets/ # Raw and processed datasets.
│ ├── raw_data.csv # Raw options data.
│ └── processed_data.csv # Cleaned data used for training.
│
├── results/ # Output files (plots, metrics, etc.)
│ ├── results_mlp.png # MLP model performance plot.
│ └── comparison.csv # Comparison of Black-Scholes and MLP results.
│
├── literature/ # Relevant literature used in the project.
│ └── papers/ # PDFs of research papers.
│
└── README.md # Project overview and setup instructions.

Setup and Installation Instructions
Follow these steps to set up and run the project locally.

Prerequisites
Make sure you have the following dependencies installed:

Python 3.x
pandas (for data manipulation)
numpy (for numerical operations)
matplotlib (for plotting and visualizations)
scikit-learn (for machine learning utilities)
torch (for neural networks with PyTorch)
jupyter (for running notebooks)
Installation Instructions

Clone the repository:
git clone https://github.com/moraestopia/cmse492_project
cd cmse492_project

Install the dependencies:
pip install -r requirements.txt

Explore the dataset:
jupyter notebook data_exploration/data_exploration.ipynb

Run the Black-Scholes model:
python black_scholes/black_scholes.py

Train the MLP model:
python MLP/train_mlp.py

View the results:
Check the results/ directory for evaluation metrics and plots.

Dependencies
Below is a summary of the dependencies required for the project:

Python 3.x: Programming language.
pandas: Data manipulation library.
numpy: Numerical operations.
matplotlib: For creating visualizations.
scikit-learn: Utilities for machine learning models.
torch: PyTorch framework for building neural networks.
jupyter: Interface for running notebooks.
How to Contribute
Feel free to fork the repository, make improvements, and submit a pull request. Any feedback or suggestions are welcome.

Contact
For questions or support, please refer to the project GitHub repository:
https://github.com/moraestopia/cmse492_project

