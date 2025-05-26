# Data Cleaning and Preprocessing with Python

This repository contains a Jupyter Notebook (`Task1.ipynb`) that demonstrates basic data cleaning and preprocessing techniques using Python and the `pandas` library.

## 📌 Objective

The primary goal of this notebook is to prepare raw data for analysis by performing the following tasks:

- Identifying and handling missing values
- Removing duplicate rows
- Standardizing categorical text values (e.g., gender, country names)
- Converting date formats to a consistent type (`dd-mm-yyyy`)
- Renaming column headers to be clean and uniform (e.g., lowercase, no spaces)
- Checking and correcting data types (e.g., `age` as integer, `date` as datetime)

## 🛠 Tools Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy (if applicable)


## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/saikumarponnapati/task1.git
   cd task1
2. Install required libraries:
    ```bash
    pip install pandas jupyter
    
3. Launch the Jupyter Notebook:
     ```bash
    jupyter notebook Task1.ipynb

## ✅ Key Functions Used

df.isnull(), df.fillna()

df.drop_duplicates()

str.strip(), str.lower(), str.replace()

pd.to_datetime()

df.columns.str.strip().str.lower().str.replace(' ', '_')

df.astype(), pd.to_numeric()

## 📌 Notes

Be sure to inspect your dataset before and after cleaning to validate changes.

Use .info() and .describe() to get a better overview of your data.

## 📃 License

This project is open source and available under the MIT License.
