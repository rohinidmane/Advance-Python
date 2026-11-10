# 🚕 NYC Taxi Trips – Exploratory Data Analysis (EDA)

A Python data analysis project that explores the **NYC Taxi Trips Dataset** using Pandas, NumPy, Matplotlib, and Seaborn. This project analyzes taxi fares, trip distances, trip durations, pickup hours, and daily trip patterns to identify meaningful trends and insights.

---

## 📊 What This Project Does

This project performs Exploratory Data Analysis (EDA) on NYC taxi trip records.

It helps to understand:

- 🚕 Taxi Fare Distribution
- 📏 Trip Distance Analysis
- ⏱️ Trip Duration Analysis
- 🕒 Pickup Hour Analysis
- 📅 Daily Trip Patterns
- 🔍 Relationships Between Different Variables
- 📊 Correlation Analysis
- 💡 Business Insights

---

## 🔄 Data Analysis Workflow

 Dataset Collection
        ↓
 Basic Data Exploration
        ↓
 Missing Values & Duplicate Checking
        ↓
 Data Type Conversion
        ↓
 Feature Engineering
        ↓
 Univariate Analysis
        ↓
 Bivariate Analysis
        ↓
 Multivariate Analysis
        ↓
 Time-Based Analysis
        ↓
 Key Insights & Findings

---

## 📊 Dataset

| Property        | Details |

| Dataset Name    | **NYC Taxi Trips Dataset** |
| Source          | Seaborn GitHub Repository |
| File Format     | CSV |
| Target Variable | Not Applicable (EDA Project) |
| Main Features   | Fare, Distance, Pickup, Dropoff, Passenger Count |

### Key Features

- `pickup` – Date and time when the taxi trip started.
- `dropoff` – Date and time when the taxi trip ended.
- `passengers` – Number of passengers.
- `distance` – Total trip distance.
- `fare` – Taxi trip fare.
- `trip_duration` – Total trip duration in minutes.
- `pickup_hour` – Hour of the day when the trip started.
- `pickup_day` – Day of the week when the trip started.

---

## 🧠 Key Concepts Covered

**1. Basic Data Overview**

Using `info()` and `describe(include='all')` to understand dataset structure, column information, and statistical summaries.

**2. Missing Values & Duplicates**

Using `isnull().sum()` and `duplicated().sum()` to identify missing values and duplicate records.

**3. Data Type Conversion**

Using `pd.to_datetime()` to convert pickup and dropoff columns into datetime format.

**4. Feature Engineering**

Creating new features from existing data:

- `trip_duration` – Calculates trip duration in minutes.
- `pickup_hour` – Extracts the pickup hour.
- `pickup_day` – Extracts the pickup day name.

**5. Univariate Analysis**

Analyzing individual variables using histograms and count plots.

- Fare Distribution
- Trip Duration Distribution
- Distance Distribution
- Trips by Pickup Hour

**6. Bivariate Analysis**

Understanding relationships between two variables using scatter plots and box plots.

- Fare vs Trip Duration
- Fare vs Distance
- Fare by Pickup Hour

**7. Multivariate Analysis**

Using correlation heatmaps and pair plots to understand relationships between multiple numerical variables.

**8. Time-Based Analysis**

Analyzing taxi trip patterns based on pickup time and day.

- Average Fare by Hour
- Trips by Day
- Peak Pickup Hour

**9. Key Insights**

Calculating important statistics:

- Average Fare
- Average Distance
- Average Trip Duration
- Peak Pickup Hour

---

## 📈 Visualizations Used

| Visualization | Purpose |
|---|---|
| 📊 Histogram | Analyze fare, distance, and trip duration distributions |
| 📉 Count Plot | Identify trips by pickup hour and day |
| 🔵 Scatter Plot | Analyze relationships between fare, distance, and duration |
| 📦 Box Plot | Compare fare distributions across pickup hours |
| 🔥 Heatmap | Identify correlations between numerical variables |
| 🔗 Pair Plot | Visualize relationships between multiple features |
| 📈 Line Plot | Analyze average fare by pickup hour |

---

## 🛠️ Tech Stack

 Python
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Jupyter Notebook

---

## 💡 Key Business Insights

1. **Understand Fare Patterns** – Analyze average taxi fares to understand pricing trends.
2. **Identify Peak Hours** – Find the busiest pickup hours to understand customer demand.
3. **Analyze Trip Duration** – Understand how long taxi trips generally take.
4. **Study Distance Patterns** – Explore the relationship between trip distance and fare.
5. **Understand Daily Demand** – Identify which days have higher taxi trip activity.
6. **Data-Driven Decisions** – Use EDA insights to improve taxi operations and resource planning.

---

## 📁 Project Structure

```text
NYC_Taxi_Trips_EDA/
│
├── NYC_Taxi_Trips.csv
├── NYC_Taxi_Trips_EDA.ipynb
└── README.md
```

---

## 🚀 Future Improvements

-  Build a Machine Learning model to predict taxi fares.
-  Perform advanced outlier detection and treatment.
-  Analyze pickup and dropoff locations.
-  Predict peak taxi demand hours.
-  Develop an interactive dashboard using Power BI or Streamlit.
-  Perform advanced statistical analysis.