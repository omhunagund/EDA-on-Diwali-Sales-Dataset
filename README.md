# Exploratory Data Analysis on Diwali Sales Dataset

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a Diwali Sales dataset to understand consumer purchasing behavior, product performance, and regional sales trends. The analysis involves data cleaning, preprocessing, statistical exploration, and visualization using Python. Multiple visualizations were created to identify important customer segments, popular product categories, high-performing regions, and purchasing patterns during the Diwali festive season.

---

## 🎯 Objective
The objective of this project is to conduct a detailed Exploratory Data Analysis (EDA) on the Diwali Sales dataset to gain meaningful insights into consumer buying behavior, product performance, and regional sales patterns.

---

## 🛠 Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation and data cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization

---

## 📂 Dataset
The project uses the **Diwali Sales Dataset**, which contains customer and transaction-related information collected during the Diwali shopping season.

The dataset contains information related to factors such as:
- Gender
- Age
- Age Group
- Marital Status
- State
- Zone
- Occupation
- Product Category
- Orders
- Purchase Amount

---

## 🔄 Project Workflow

```text
Dataset
  ↓
Data Import
  ↓
Data Exploration
  ↓
Data Cleaning
  ↓
Data Preprocessing
  ↓
Exploratory Data Analysis
  ↓
Visualization
  ↓
Insight Generation
  ↓
Export Cleaned Dataset
```

---

## 🧹 Data Cleaning & Preprocessing
The following data preparation steps were performed:
- Imported the dataset using Pandas.
- Handled character encoding issues while loading the dataset using `unicode_escape`.
- Examined the dataset structure, shape, columns, data types, and missing values.
- Removed unnecessary columns where applicable.
- Handled missing/null values.
- Removed duplicate records.
- Converted relevant columns into suitable data types.
- Prepared the cleaned dataset for analysis.
- Exported the cleaned dataset as `diwali_cleaned.csv`.

---

## 📊 Exploratory Data Analysis
A total of 10 visualizations were created to analyze different aspects of the Diwali sales data.

**1. Gender-wise Purchase**
Analyzed total purchase amount across male and female customers to identify the dominant spending group.
*Insight:* Female customers contributed significantly more to total sales than male customers, making them the dominant buyer group in the dataset.

**2. Age Group vs Purchase Amount**
Analyzed purchasing behavior across different age groups.
*Insight:* The 26–35 age group contributed the highest purchase amount, indicating strong purchasing activity among young adults.

**3. State-wise Sales**
Compared total sales across states to identify the highest-performing regions.
*Insight:* Uttar Pradesh, Maharashtra, and Karnataka were among the leading states in terms of overall sales.

**4. Occupation vs Purchase**
Analyzed total purchase amount across different occupational groups.
*Insight:* Customers from occupations such as IT, Healthcare, and Aviation showed relatively high spending patterns.

**5. Product Category Popularity**
Compared product categories based on sales activity.
*Insight:* Food, Clothing & Apparel, and Electronics were among the most prominent product categories in the dataset.

**6. Marital Status vs Purchase**
Compared purchase behavior between married and unmarried customers.
*Insight:* Unmarried customers recorded a higher overall purchase amount compared with married customers.

**7. Top Cities by Sales**
Identified the cities contributing the highest total sales.
*Insight:* A relatively small number of cities contributed a significant portion of the overall sales, highlighting important regional markets.

**8. Purchase Amount Distribution**
Used a histogram to understand how purchase amounts were distributed.
*Insight:* Most purchases were concentrated within a moderate spending range, while a smaller number of high-value purchases created a right-skewed distribution.

**9. Purchase by Gender – Boxplot**
Used a boxplot to compare purchase distributions between male and female customers.
*Insight:* Female customers showed a higher overall purchase distribution, although variation and high-value purchases were present within both groups.

**10. Gender vs Product Category**
Compared product category purchases across genders.
*Insight:* Female customers showed stronger participation across several major product categories, particularly categories such as Food and Clothing.

---

## 🔍 Key Findings
The major findings from the analysis are:
- Female customers are the dominant contributors to overall sales.
- Customers aged 26–35 represent the highest-spending age group.
- Several states, particularly Uttar Pradesh, Maharashtra, and Karnataka, contribute significantly to total sales.
- Customers working in occupations such as IT, Healthcare, and Aviation show strong purchasing activity.
- Food, Clothing & Apparel, and Electronics are among the major product categories.
- Unmarried customers contribute a higher overall purchase amount than married customers.
- Sales are concentrated in a smaller set of high-performing cities and regions.
- Most customers fall within a moderate purchase range, with a limited number of high-value transactions.
- Gender-based analysis indicates stronger spending activity among female customers.
- The analysis demonstrates that customer demographics, occupation, product category, and geography all provide useful information for understanding festive-season purchasing behavior.

---

## ⚠️ Challenges Faced & Solutions

**1. Encoding Error While Loading the Dataset**
The dataset initially caused a UTF-8 decoding error.

*Solution:* The dataset was loaded using the `unicode_escape` encoding:
```python
df = pd.read_csv("Diwali Sales Data.csv", encoding="unicode_escape")
```

**2. Missing and Duplicate Data**
The dataset contained missing values and duplicate records.

*Solution:* Missing records and duplicates were identified and handled using Pandas functions such as `dropna()` and `drop_duplicates()`.

**3. Visualization Label Overlap**
Some product category names overlapped in the visualizations because of the large number of categories.

*Solution:* Figure dimensions and axis-label orientation were adjusted, and horizontal bar charts were used where appropriate to improve readability.

---

## 📁 Project Files
```
EDA-on-Diwali-Sales-Dataset/
│
├── Diwali Sales Data.csv
├── diwali_cleaned.csv
├── EDA on Diwali Sales Dataset.ipynb
└── README.md
```
> File names may vary depending on the final names used in the repository.

---

## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/omhunagund/EDA-on-Diwali-Sales-Dataset.git
   ```
2. Navigate to the project directory
   ```bash
   cd EDA-on-Diwali-Sales-Dataset
   ```
3. Install the required libraries
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
4. Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```
5. Open the notebook
   Open the `.ipynb` file and run the cells sequentially.

---

## 📌 Project Outcome
The project demonstrates how Exploratory Data Analysis can be used to transform raw sales data into meaningful business insights. The analysis highlights important customer segments, high-performing locations, popular product categories, and spending patterns that can help businesses make more informed decisions during festive sales campaigns.

---

## 👤 Author
**Om Hunagund**
GitHub: [github.com/omhunagund](https://github.com/omhunagund)
