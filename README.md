
#  Migration Rate Analysis (1990–2020)

This project explores global migration trends using data from the United Nations Development Programme (UNDP), focusing on net migration rates from 1990 to 2020. The goal is to apply data preprocessing and analysis techniques to uncover key insights, identify patterns, and answer specific analytical questions.

---

##  Dataset Description

The dataset contains yearly migration data for numerous countries over three decades. Each record includes:

- **Country name**
- **Year (1990 to 2020, every 5 years)**


The migration rate is calculated using the formula:

###  Migration Rate Formula

\[
\text{Migration Rate} = \frac{(\text{Migration In} - \text{Migration Out}) \times 1000}{\text{Population}}
\]

---

##  Section 1: Preprocessing

Prior to conducting any analysis, the dataset undergoes essential preprocessing steps:

1. **Remove Irrelevant Countries:**
   - Exclude countries with *missing migration rate data for all years*.

2. **Impute Missing Values:**
   - For countries with partial missing values, fill in the gaps using the **country's average migration rate**.

These steps ensure a consistent and clean dataset for meaningful analysis.

---

##  Section 2: Analytical Tasks

The project aims to answer the following questions:

###  1. Find the Top 3 Countries by Migration Rate (2020)

- Objective: Identify the **top 3 countries** with the highest migration acceptance rates in the year **2020**.
- Result is stored in the list:  
  ```python
  top_countries = [...]
  ```

###  2. Calculate the Average Migration Rate for Iran (1990–2020)

- Objective: Compute the **30-year average** net migration rate for **Iran**.
- Result is stored in the variable:  
  ```python
  iran_mean = ...
  ```

###  3. Identify the Country with the Highest Growth in Migration Rate

- Objective: Determine the country that experienced the **greatest growth** in migration rate between **1990 and 2020**.
- The growth is calculated as the **difference between the migration rate in 2020 and 1990**.

---

##  Project Files

```
.
├── Migration_Analysis.ipynb
├── migration_rate.csv
└── README.md
```

---

##  Tools & Technologies

- **Python**: For scripting and analysis.
- **Pandas**: Data preprocessing, manipulation.
- **NumPy**: Efficient numerical operations.
- **Matplotlib / Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive development and documentation.

-
