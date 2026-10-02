# 🏠 Real Estate Data Analysis using Python

A data analysis project focused on exploring and understanding real-estate property data using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

The project covers data cleaning, preprocessing, exploratory data analysis (EDA), and visualization to identify useful patterns and insights from property listings.

---

## 📌 Project Overview

This project analyzes a real-estate dataset containing information about properties such as:

* 💰 Price
* 📍 Locality
* 📐 Area
* 🏢 Property Type
* 🛏️ BHK Count
* 🏗️ Builder Name
* ✅ RERA Approval
* 🏘️ Society
* 🏠 Flat Type
* 📊 Rate per Square Foot
* 🚧 Property Status

The main objective is to clean the raw dataset, perform exploratory analysis, and understand the factors associated with property prices.

---

## 🎯 Objectives

* Clean and preprocess the raw real-estate dataset
* Handle duplicate records and inconsistent values
* Convert columns into appropriate data types
* Analyze property prices and areas
* Explore relationships between price, area, BHK, and rate per sq. ft.
* Identify patterns across localities and property types
* Create meaningful data visualizations
* Generate insights that can support real-estate analysis

---

## 🛠️ Technologies Used

| Technology                   | Purpose                      |
| ---------------------------- | ---------------------------- |
| 🐍 Python                    | Data analysis                |
| 🐼 Pandas                    | Data cleaning & manipulation |
| 🔢 NumPy                     | Numerical operations         |
| 📊 Matplotlib                | Data visualization           |
| 📈 Seaborn                   | Statistical visualization    |
| 📄 CSV                       | Dataset format               |
| 💻 Jupyter Notebook / Python | Development environment      |

---

## 📂 Dataset

The dataset contains **19,515 property records** and **12 columns**.

### Main Features

| Column          | Description                  |
| --------------- | ---------------------------- |
| `Price`         | Property price               |
| `Status`        | Construction/property status |
| `Area`          | Property area                |
| `Rate per sqft` | Price per square foot        |
| `Property Type` | Type of property             |
| `Locality`      | Property location            |
| `Builder Name`  | Builder/developer            |
| `RERA Approval` | RERA approval status         |
| `BHK_Count`     | Number of bedrooms           |
| `Socity`        | Society/project name         |
| `Company Name`  | Company/builder information  |
| `Flat Type`     | Type of flat/property        |

---

## 🧹 Data Cleaning

The project includes several preprocessing steps:

* Removed unnecessary spaces from column names
* Converted column names to lowercase
* Replaced spaces with underscores
* Removed duplicate records
* Converted price values into numerical format
* Cleaned area values
* Converted rate-per-square-foot values into numerical format
* Prepared categorical and numerical columns for analysis

Example:

```python
df.columns = df.columns.str.strip().str.lower().str.replace(' ', '_')

df = df.drop_duplicates()

df.price = df.price.astype(str).str.replace(',', '').astype(float)
```

---

## 📊 Exploratory Data Analysis

The analysis explores questions such as:

* Which properties have the highest prices?
* How does property area relate to price?
* How does BHK count affect property prices?
* Which localities contain more properties?
* What is the distribution of property prices?
* How does rate per square foot vary?
* What types of properties are most common?
* How does RERA approval vary across properties?

---

## 📈 Data Visualization

The project uses **Matplotlib and Seaborn** to create visualizations for better understanding of the dataset.

Visualizations can include:

* Price distribution
* Area distribution
* Price vs. Area
* BHK vs. Price
* Property type distribution
* Locality analysis
* Rate per square foot analysis
* Correlation heatmaps

---

## 🔍 Key Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Handling Missing/Inconsistent Data
* Feature Analysis
* Extracting Business Insights

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project folder

```bash
cd real-estate-data-analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Make sure the dataset is in the project directory

```text
real-estate-data-analysis/
│
├── data.csv
├── CWH PYTHON PROJECT
└── README.md
```

### 5. Run the Python project

```bash
python "CWH PYTHON PROJECT"
```

---

## 💡 Project Outcome

The project demonstrates how raw real-estate data can be transformed into structured information and analyzed to discover meaningful patterns.

It also provides hands-on experience in the complete basic data-analysis workflow:

**Raw Data → Data Cleaning → Data Exploration → Visualization → Insights**

---

## 👨‍💻 About Me

I'm an aspiring **Data Analyst** interested in turning raw data into meaningful insights using Python, SQL, Excel, Power BI, and data visualization.

I'm continuously improving my analytical and technical skills by working on practical projects and solving real-world data problems.

---

## 🔗 Connect With Me

**GitHub:**
https://github.com/Aryan349409

**LinkedIn:**
www.linkedin.com/in/aryanrai-dataanalyst

---

## ⭐ If You Like This Project

If you found this project useful, feel free to ⭐ **star the repository** and connect with me on GitHub and LinkedIn.

---

### 📌 Tags

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Data Analysis` `EDA` `Data Visualization` `Real Estate Analytics`
