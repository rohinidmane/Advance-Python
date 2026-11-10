# 🌸 Iris Dataset – Data Analysis Using Pandas

A Python data analysis project that explores the **Iris Dataset** using Pandas and NumPy. This project focuses on data loading, data inspection, statistical analysis, unique values, column selection, and filtering records based on specific conditions.

---

## 📊 What This Project Does

This project performs basic data exploration and filtering on the Iris dataset.
It helps to understand flower measurements and identify different Iris species using:

- 🌸 Dataset Exploration
- 🔍 Data Inspection
- 📊 Statistical Analysis
- 🏷️ Unique Value Identification
- 🎯 Column Selection
- 🔎 Data Filtering
- 📈 Conditional Data Analysis

---

## 🔄 Data Analysis Workflow

 Load Iris Dataset (CSV)
            ↓
 Explore Dataset Information
            ↓
 Perform Statistical Analysis
            ↓
 Identify Columns and Unique Values
            ↓
 Select Specific Columns
            ↓
 Filter Records Using Conditions
            ↓
 Analyze Filtered Data

---

## 📊 Dataset

| Property | Details |
|---|---|
| Dataset Name    | **Iris Dataset** |
| Total Records   | **150**          |
| Input Features  | **4**            |
| Target Variable | `Species`        |
| File Format     | CSV              |
| Library Used    | Pandas           |

### Key Features

- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species`

### Iris Species

- 🌸 Iris-setosa
- 🌼 Iris-versicolor
- 🌺 Iris-virginica

---

## 🧠 Key Concepts Covered

**1. Loading Dataset**

Using `pd.read_csv()` to import the Iris dataset from a CSV file.

**2. Dataset Information**

Using `df.info()` to understand column names, data types, and non-null values.

**3. Statistical Analysis**

Using `df.describe()` to calculate count, mean, standard deviation, minimum, maximum, and quartile values.

**4. Column Exploration**

Using `df.columns` to display column names.

**5. Unique Values**

Using `unique()` and `nunique()` to identify unique values and count distinct values.

**6. Column Selection**

Selecting individual and multiple columns from the dataset.

**7. Data Filtering**

Filtering records based on specific conditions, such as:

- Displaying only Iris-setosa records.
- Selecting flowers with SepalLengthCm greater than or equal to 5.
- Filtering records where PetalWidthCm equals 0.4.
- Applying multiple conditions using `&` operator.

**8. Data Analysis**

Using `min()`, `max()`, and `len()` to analyze filtered records.

---

## 🛠️ Tech Stack

🐍 Python

🐼 Pandas

🔢 NumPy

📓 Jupyter Notebook

---

## 📈 Operations Performed

| Operation | Purpose |
|---|---|
| `read_csv()` | Load CSV dataset |
| `info()`     | Display dataset information |
| `describe()` | Generate statistical summary |
| `columns`    | Display column names |
| `unique()`   | Find unique values |
| `nunique()`  | Count unique values |
| `dir()`      | Explore available attributes and methods |
| 'Column Selection' | Select specific columns |
| 'Conditional Filtering' | Filter records based on conditions |
| `min()`      | Find minimum value |
| `max()`      | Find maximum value |
| `len()`      | Count filtered records |

---

## 📁 Project Structure

```text
Iris_Dataset/
│
├── Iris.csv
├── Iris_Dataset.ipynb
└── README.md
```

---

## 🚀 Future Improvements

- 📊 Perform Exploratory Data Analysis (EDA).
- 📈 Create visualizations using Matplotlib and Seaborn.
- 🔍 Identify relationships between flower measurements.
- 🤖 Apply Machine Learning classification algorithms.
- 🎯 Predict Iris flower species using classification models.