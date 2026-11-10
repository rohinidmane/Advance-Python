# 🐼 Pandas – Data Manipulation and Analysis

A Python programming project that introduces **Pandas**, an open-source Python library used for data manipulation and analysis. This project covers Pandas Series, DataFrames, data creation, data inspection, statistical summaries, and column renaming.

---

## 📊 What This Project Does

This project demonstrates the fundamental concepts and operations of Pandas.

It helps to understand:

-  Introduction to Pandas
-  Importing Pandas and NumPy
-  Pandas Series
-  Pandas DataFrame
-  Creating Series and DataFrames
-  Indexing and Accessing Elements
-  Data Inspection
-  Statistical Analysis
-  Renaming Columns

---

## 🔄 Pandas Workflow

 Import Pandas and NumPy
            ↓
 Create Pandas Series
            ↓
 Create Pandas DataFrames
            ↓
 Access and Inspect Data
            ↓
 Perform Statistical Analysis
            ↓
 Rename Columns
            ↓
 Manipulate and Analyze Data

---

## 📊 Data Structures in Pandas

Pandas provides two main data structures:

**1. Pandas Series**

A Pandas Series is a one-dimensional labeled array that can store different types of data, such as integers, strings, and floats.

Key Operations:
- Creating a Series using `pd.Series()`.
- Assigning custom indexes.
- Assigning a Series name.
- Accessing elements using labels and positions.

**2. Pandas DataFrame**

A Pandas DataFrame is a two-dimensional data structure containing rows and columns with labeled axes.

Key Operations:
- Creating DataFrames using NumPy arrays.
- Creating DataFrames using lists of lists.
- Creating DataFrames using dictionaries of lists.
- Assigning row indexes and column names.

---

## 🧠 Key Concepts Covered

**1. Importing Libraries**

Using `import pandas as pd` and `import numpy as np` to import the required libraries.

**2. Creating Pandas Series**

Using `pd.Series()` to create one-dimensional labeled data structures.

**3. Accessing Series Elements**

- `series['c']` – Access elements using index labels.
- `series.iloc[1]` – Access elements using integer positions.

**4. Creating DataFrames**

Creating two-dimensional DataFrames using:

- NumPy arrays.
- Lists of lists.
- Dictionaries of lists.

**5. Data Inspection**

Using different Pandas methods to understand dataset structure and contents.

**6. Statistical Summary**

Using `describe()` to generate statistical information such as mean, standard deviation, minimum, maximum, and quartiles.

**7. Viewing Data**

- `head()` – Displays the first five rows by default.
- `tail()` – Displays the last five rows by default.

**8. Column Information**

Using `columns` to display all column names.

**9. Renaming Columns**

Using `rename()` to change existing column names.

- `inplace=True` – Applies changes directly to the original DataFrame.

---

## 🛠️ Tech Stack

 Python
 Pandas
 NumPy
 Jupyter Notebook

---

## 📈 Operations Performed

| Operation | Purpose |
|---|---|
| `pd.Series()` | Create a Pandas Series |
| `pd.DataFrame()` | Create a DataFrame |
| `np.random.randint()` | Generate random integers |
| `np.random.randn()` | Generate random numbers |
| `info()` | Display DataFrame information |
| `describe()` | Generate statistical summary |
| `head()` | Display first rows |
| `tail()` | Display last rows |
| `columns` | Display column names |
| `rename()` | Rename DataFrame columns |
| `iloc[]` | Access elements using integer positions |

---

## 💡 Key Learnings

1. Understand the importance of Pandas in data analysis.
2. Learn the difference between Series and DataFrame.
3. Create Series using lists and custom indexes.
4. Create DataFrames using NumPy arrays, lists, and dictionaries.
5. Access Series elements using labels and positions.
6. Inspect datasets using Pandas methods.
7. Generate statistical summaries using `describe()`.
8. Rename DataFrame columns using `rename()`.

---

## 📁 Project Structure

Pandas
│
├── Pandas.ipynb
└── README.md
```

---

## 🚀 Future Improvements

-  Explore data selection and filtering.
-  Handle missing values and duplicate records.
-  Perform data sorting and grouping.
-  Learn Pandas merging and joining.
-  Perform advanced data analysis.
-  Integrate Pandas with Matplotlib and Seaborn for visualization.