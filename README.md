
# Neural Network Models as an Alternative to the Black-Scholes Equation for Option Pricing

## **Project Description**
This project explores the use of **Multi-Layer Perceptrons (MLPs)** to predict option prices, offering a data-driven alternative to the traditional **Black-Scholes model**. While Black-Scholes provides a closed-form solution for European options, it assumes ideal market conditions (e.g., constant volatility, no transaction costs) and struggles with real-world challenges like the **volatility smile**. In contrast, neural networks can learn complex, nonlinear pricing dynamics from historical data. 

The project aims to compare the performance of MLP models and Black-Scholes using **Mean Squared Error (MSE)** and **Mean Absolute Percentage Error (MAPE)** as evaluation metrics.

---

## **Project Objectives**
- Implement **Multi-Layer Perceptrons (MLPs)** for option pricing.
- Use **Black-Scholes** as a baseline for comparison.
- Evaluate the models using real-world options data from **OptionMetrics IvyDB EU**.
- Generate **synthetic data** if necessary to improve robustness.
- Compare the results based on **MSE** and **MAPE** metrics.

---

## **Repository Structure**
```
cmse492_project/
│
├── MLP/                # Scripts for defining and training MLP models.
│   ├── training    # Main folder with scripts to train the MLP model.
│   └── evaluation  # Evaluates the performance of the MLP model.
│   └── models      # Saved models.
│
├── black_scholes/      # Implementation of the Black-Scholes model.
│   └── # Baseline option pricing script.
│
├── data_exploration/   # Notebooks for exploratory data analysis.
│   └── data_exploration.ipynb # Jupyter notebook for data exploration.
│
├── datasets/           # Raw and processed datasets.
│   ├── adidas_tick_options.csv    # Raw options data.
│   └── call_options.csv # Data with European and American style Call Options
│   └── put_options.csv # Data with European and American style Put Options
│   └── call_eu_options.csv # Data with European style Call Options
│   └── put_eu_options.csv # Data with European style Put Options
│
├── results/            # Output files (plots, metrics, etc.)
│   ├── # MLP model performance plots.
│   └── # Comparison of Black-Scholes and MLP results.
│   └── # Comparison of Black-Scholes and MLP results (tables).
│
├── literature/         # Relevant literature used in the project.
│   └── # PDFs of research papers.
│
└── README.md           # Project overview and setup instructions.
```

---

## **Setup and Installation Instructions**
Follow these steps to set up and run the project locally.

### **Prerequisites**
Make sure you have the following dependencies installed:
- **Python 3.x**
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)
- `matplotlib` (for plotting and visualizations)
- `scikit-learn` (for machine learning utilities)
- `torch` (for neural networks with PyTorch)
- `jupyter` (for running notebooks)

### **Installation Instructions**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/moraestopia/cmse492_project
   cd cmse492_project
   ```

2. **Explore the dataset**:
   ```bash
   jupyter notebook data_exploration/data_exploration.ipynb
   ```

3. **Run the Black-Scholes model**:

4. **Train the MLP model**:

5. **View the results**:
   Check the `results/` directory for evaluation metrics and plots.

---

## **Dependencies**
Below is a summary of the dependencies required for the project:
- **Python 3.x**: Programming language.
- **pandas**: Data manipulation library.
- **numpy**: Numerical operations.
- **matplotlib**: For creating visualizations.
- **scikit-learn**: Utilities for machine learning models.
- **torch**: PyTorch framework for building neural networks.
- **jupyter**: Interface for running notebooks.

---

## **How to Contribute**
Feel free to fork the repository, make improvements, and submit a pull request. Any feedback or suggestions are welcome.

---

## **Contact**
For questions or support, please refer to moraesjo(at)msu(dot)edu

---
