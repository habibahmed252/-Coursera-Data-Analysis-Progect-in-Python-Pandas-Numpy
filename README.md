# -Coursera-Data-Analysis-Progect-in-Python-Pandas-Numpy
# 📊 Python for Data Analysis: NumPy & Pandas Fundamentals

> **Coursera Project & Hands-on Exercises**  
> This repository contains code, mini-challenges, and a final capstone project showcasing fundamental data analysis skills using **Python**, **NumPy**, and **Pandas**.

---

## 🛠️ Technologies Used
* **Python** 
* **NumPy** (Linear Algebra & Multidimensional Arrays)
* **Pandas** (Data Manipulation, Cleaning & Analysis)

---

## 📚 Topics & Tasks Covered

This project is structured into step-by-step tasks and practical mini-challenges:

### **NumPy Fundamentals**
1. **Single & Multi-Dimensional Arrays:** Creating 1D arrays and 2D matrices, checking data types, and defining custom arrays.
2. **Built-in Methods & Functions:** Generating random distributions (`rand`, `randint`), evenly spaced sequences (`arange`), identity matrices (`eye`), zeros, and ones.
3. **Mathematical Operations:** Performing vector/matrix arithmetic, calculating distances between data points, and applying math functions.
4. **Slicing & Indexing:** Accessing specific rows/columns, extracting subsets, and broadcasting values.
5. **Conditional Selection:** Filtering arrays and replacing elements based on specific conditions (e.g., negative/positive, odd/even values).

### **Pandas Fundamentals**
6. **DataFrames & Series:** Introduction to Pandas data structures, creating DataFrames from dictionaries.
7. **Reading External Data:** Loading data from CSV files and scraping tabular data from web pages (HTML tables).
8. **Pandas Operations:** Filtering data, dropping columns, and performing aggregate calculations (e.g., finding high net-worth individuals).
9. **Applying Functions:** Customizing and updating DataFrame values using user-defined functions and `.apply()`.
10. **Sorting & Ordering:** Sorting DataFrames by specific columns (`inplace=True`).
11. **Concatenating & Merging:** Combining multiple datasets using `pd.concat` and `pd.merge` based on shared keys (Client IDs).

---

## 🚀 Final Project: Bank Client Management System

As a capstone task, I built a mini-project simulating a bank client database:
* Created and populated multiple client DataFrames (`Bank_df_1`, `Bank_df_2`).
* Merged client profile information with financial/salary records using unique Client IDs.
* Handled dataset concatenation to include newly registered clients (e.g., adding a new record dynamically).

---

## 💡 How to Run the Notebook

1. Clone this repository or download the `.ipynb` file.
2. Open it using **Jupyter Notebook**, **JupyterLab**, or upload it to **Google Colab**.
3. Make sure you have the required libraries installed:
   ```bash
   pip install numpy pandas
