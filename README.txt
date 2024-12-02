# CMSE492 Project

## Instructions to Run the Scripts

1. **Set Up the Environment**:
   - Ensure you have Python installed (preferably version 3.8 or higher).

2. **Running Black-Scholes Models**:
   - Navigate to the `black_scholes/` directory:
     ```bash
     cd black_scholes/
     ```
   - Run any of the provided Jupyter Notebooks:
     jupyter notebook {equity}_calls_bs_model.ipynb

     ** Current equity options: btc, vale3, petr4

3. **Running Neural Network Models**:
   - Go to the `models/training/` directory:
     ```bash
     cd models/training/
     ```
   - Open the Jupyter Notebooks and run them

4. **Data Exploration**:
   - Explore the datasets in the `data_exploration/` directory. Open the notebooks:
     ```bash
     jupyter notebook btc_data_exploration.ipynb
     ```

5. **Viewing Results**:
   - Final results are stored in the `results/` directory. Open the `final_report.pdf` for detailed insights.

---



cmse492_project/
│
├── MLP/
│   ├── training/
│   └── ...
│
├── black_scholes/
│   |── btc_calls_bs_model.ipynb # Runs the Black-Scholes for the Bitcoin data
|   └── petr4_calls_bs_model.ipynb # Runs the Black-Scholes for PETR4
|   └── vale3_calls_bs_model.ipynb # Runs the Black-Scholes for VALE3
│
├── data_exploration/
│   └── addyy_data_exploration.ipynb # Dirty Adidas Dataset (KNN imputation, etc. - WASN'T used)
│   └── btc_data_exploration.ipynb # Preprocessing and Exploration of our BTC data
│
│
├── models/ # Contains all of the scripts that yield the results mentioned in the Report
│   └── training # GO HERE TO RUN THE SCRIPTS
│
├── results/
│   ├── final_report.pdf
│   └── ...
│
├── .gitignore
├── README.md
└── requirements.txt
