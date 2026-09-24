# 📊 Statistics Practice with Seaborn Datasets

This project is a **Statistics and Data Visualization practice project** based on two datasets available through Seaborn:

- 💎 **Diamonds Dataset**
- 🚢 **Titanic Dataset**

The project was created to practice statistical concepts using Python, Pandas, Seaborn, Matplotlib, NumPy, and Plotly.

---

## 🎯 Project Objective

The main objective of this project is to understand and apply basic statistical concepts on real datasets rather than only studying the formulas theoretically.

The analysis covers:

- Measures of Central Tendency
- Measures of Dispersion
- Quartiles and Percentiles
- Interquartile Range (IQR)
- Outlier Detection
- Grouped Statistics
- Distribution and Skewness
- Coefficient of Variation
- Data Visualization
- Relationship between variables

---

## 📚 Concepts Covered

### 1. Central Tendency

For numerical variables, the project calculates:

- Mean
- Median
- Mode

### 2. Measures of Dispersion

The project calculates:

- Minimum
- Maximum
- Range
- Variance
- Standard Deviation

### 3. Quartiles and IQR

The analysis includes:

- Q1 (25th percentile)
- Q2 / Median (50th percentile)
- Q3 (75th percentile)
- IQR

Formula:

```text
IQR = Q3 - Q1
```

### 4. Outlier Detection

The IQR method is used to identify potential outliers.

```text
Lower Bound = Q1 - 1.5 × IQR
Upper Bound = Q3 + 1.5 × IQR
```

### 5. Grouped Statistics

Statistics are calculated for different categories using Pandas `groupby()`.

Examples include:

- Diamond price by cut
- Diamond price by color
- Titanic age by sex
- Titanic fare by passenger class

### 6. Distribution and Skewness

The project uses histograms, KDE plots, and box plots to understand distributions and identify skewness.

### 7. Coefficient of Variation

The project also compares relative dispersion using:

```text
CV = (Standard Deviation / Mean) × 100
```

---

## 💎 Diamonds Dataset Analysis

The Diamonds dataset is used to practice statistics on variables such as:

- `price`
- `carat`
- `cut`
- `color`
- `clarity`

The analysis includes:

- Mean, median and mode of price
- Minimum and maximum price
- Variance and standard deviation
- Quartiles and IQR
- Price outlier detection
- Carat statistics and outliers
- Price statistics grouped by cut
- Price statistics grouped by color

### Visualizations

The project creates visualizations such as:

- Histogram of diamond prices
- Box plot of diamond prices
- Histogram of carat
- Box plot of price by cut
- Scatter plot of carat vs price
- Combined statistical visualizations

The `carat` vs `price` scatter plot is used to investigate the relationship between diamond weight and price.

---

## 🚢 Titanic Dataset Analysis

The Titanic dataset is used to practice statistics on variables such as:

- `age`
- `fare`
- `sex`
- `class`
- `pclass`
- `survived`

The analysis includes:

- Mean, median and mode of age
- Minimum and maximum age
- Age variance and standard deviation
- Age quartiles and IQR
- Age outlier detection
- Fare statistics
- Fare quartiles and IQR
- Fare outlier detection
- Statistics grouped by sex
- Fare statistics grouped by passenger class
- Comparison of variation between groups

### Visualizations

The project creates:

- Histogram of passenger age
- Box plot of age
- Histogram of passenger fare
- Box plot of fare
- Box plot of fare by passenger class
- Box plot of age by sex
- Passenger count by class
- Survival count visualization

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Pandas | Data manipulation and statistical calculations |
| NumPy | Numerical operations |
| Seaborn | Statistical visualization and datasets |
| Matplotlib | Plotting and visualization |
| Plotly | Interactive visualization practice |
| Jupyter Notebook | Development and documentation |

---

## 📁 Project Structure

```text
```text
Statistics/
│
├── Project_s1/
│   ├── Project_details.ipynb
│   ├── session_1.ipynb
│   ├── image.png
│   └── README.md
│
└── statistics_Notes/
    └── Session 1               # Project documentation
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Open the project

Open the project folder in VS Code, Jupyter Notebook, or JupyterLab.

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### 4. Run the notebook

Open:

```text
session_1.ipynb
```

and execute the cells.

The datasets are loaded through Seaborn:

```python
import seaborn as sns

Data1 = sns.load_dataset("diamonds")
Data2 = sns.load_dataset("titanic")
```

---

## 🧠 Key Learning Outcomes

Through this project, I practiced how to:

- Load datasets using Seaborn
- Explore datasets using Pandas
- Check shape, columns, data types and missing values
- Calculate descriptive statistics
- Understand mean vs median
- Calculate variance and standard deviation
- Calculate quartiles and IQR
- Detect potential outliers using the IQR method
- Perform grouped statistical analysis
- Understand skewed distributions
- Compare distributions using visualizations
- Investigate relationships between variables using scatter plots
- Present statistical findings visually

---

## 📌 Project Focus

This is primarily a **learning and practice project** focused on building a strong foundation in statistics and exploratory data analysis.

The goal is not just to calculate statistical values, but to understand what those values and visualizations tell us about the data.

---

## 👨‍💻 Author

**Aman**

This project is part of my learning journey in **Data Science, AI/ML, and Data Engineering**.

---

⭐ If you find this project useful, feel free to explore the notebooks and visualizations.
