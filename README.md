# Salary Data Analysis

This project analyzes salary data using Python and Pandas. The dataset is loaded from a CSV file (`Salaries.csv`), and various data cleaning and transformation steps are applied to prepare it for further analysis.

## Features

- Load and inspect salary data
- Convert numerical columns to the correct data type
- Handle missing or erroneous values
- Perform exploratory data analysis (EDA)

## Installation

Ensure you have Python installed, then install the required dependencies:

```bash
pip install pandas numpy jupyter
```

You also need to have Jupyter Notebook installed to run the `.ipynb` file. You can install it using:

```bash
pip install notebook
```

Alternatively, you can install all dependencies in one command:

```bash
pip install -r requirements.txt
```

## Usage

1. Place the `Salaries.csv` file in the same directory as the notebook.
2. Open and run the Jupyter Notebook (`Code.ipynb`).
3. The notebook will:
   - Load the salary dataset
   - Display the first few rows of the dataset
   - Show summary information (column types, missing values, etc.)
   - Convert salary-related columns (`BasePay`, `OvertimePay`, `OtherPay`, `Benefits`) to numeric values while handling errors

## Dataset

- The dataset should be in CSV format and contain salary-related fields.
- Columns include `BasePay`, `OvertimePay`, `OtherPay`, and `Benefits`.

## Contributing

Feel free to fork this repository and submit pull requests for improvements or additional analysis steps.

