# 📺 Amazon Prime TV Shows – Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Amazon Prime Video content to understand patterns and trends across different attributes such as **content type, genres, release years, age certifications, runtime, ratings, votes, actors, and production countries**.

The objective is to clean, explore, visualize, and analyze the dataset to extract meaningful insights that can support **data-driven content and audience-related decisions**.

---

## 🎯 Project Objectives

The major objectives of this project are:

* Analyze the distribution of Amazon Prime content
* Understand content release trends over the years
* Analyze genres and content categories
* Study age certification and audience categories
* Analyze IMDb and TMDb ratings
* Examine the relationship between ratings, votes, runtime, and popularity
* Analyze actor appearances across titles
* Explore country-wise content and ratings
* Identify missing values and duplicate records
* Generate meaningful insights through data visualization

---

## 📂 Dataset

The analysis uses two datasets:

### `titles.csv`

Contains information related to movies and TV shows, including:

* Title
* Content type
* Description
* Release year
* Age certification
* Runtime
* Genres
* Production countries
* IMDb score
* IMDb votes
* TMDb score
* TMDb popularity
* Number of seasons

### `credits.csv`

Contains information about people associated with the content, including:

* Person name
* Character
* Role
* Title ID

The datasets are connected using the common **`id`** field.

---

## 🛠️ Tech Stack

| Technology                          | Purpose                        |
| ----------------------------------- | ------------------------------ |
| **Python**                          | Programming & analysis         |
| **Pandas**                          | Data cleaning and manipulation |
| **NumPy**                           | Numerical operations           |
| **Matplotlib**                      | Data visualization             |
| **Seaborn**                         | Statistical visualization      |
| **Jupyter Notebook / Google Colab** | Development environment        |

---

## 🔄 Project Workflow

```text
              Amazon Prime Dataset
                       │
                       ▼
                Data Loading
                       │
                       ▼
                Data Inspection
                       │
                       ▼
             Data Cleaning & Wrangling
                       │
                       ▼
             Missing Value Analysis
                       │
                       ▼
              Duplicate Analysis
                       │
                       ▼
             Univariate Analysis
                       │
                       ▼
              Bivariate Analysis
                       │
                       ▼
             Multivariate Analysis
                       │
                       ▼
              Data Visualization
                       │
                       ▼
                Insights & Findings
                       │
                       ▼
                  Conclusion
```

---

# 🔍 Exploratory Data Analysis

## 1️⃣ Univariate Analysis

Individual variables were analyzed to understand their distribution and characteristics.

The analysis includes:

* IMDb score distribution
* Runtime distribution
* Release year distribution
* Age certification distribution
* Content type distribution
* Genre distribution

---

## 2️⃣ Bivariate Analysis

Relationships between two variables were explored to identify patterns.

Examples include:

* Runtime vs IMDb score
* IMDb votes vs IMDb score
* Release year vs number of titles
* Age certification vs ratings
* Country vs IMDb score

---

## 3️⃣ Multivariate Analysis

Multiple variables were analyzed together using statistical visualizations such as:

* Correlation heatmaps
* Pair plots
* Comparative charts

These visualizations help understand relationships between multiple numerical variables.

---

# 📊 Data Cleaning & Preparation

The dataset was examined and prepared before performing analysis.

The major preprocessing steps included:

* Checking dataset shape
* Inspecting column data types
* Checking missing values
* Checking duplicate records
* Handling required missing values
* Examining numerical distributions
* Identifying potential outliers
* Preparing data for visualization and analysis

---

# 📈 Visualizations

The project uses **Matplotlib and Seaborn** to visualize important patterns in the dataset.

Some of the analyses include:

* 📊 Content distribution
* ⭐ IMDb score distribution
* 🎬 Genre analysis
* 📅 Release-year trends
* 🔞 Age certification analysis
* ⏱️ Runtime analysis
* 🌎 Country-wise analysis
* 👤 Actor appearance analysis
* 📈 IMDb votes vs IMDb score
* 🔥 Runtime vs IMDb score
* 🔗 Correlation heatmap
* 📉 Pair plot

---

# 💡 Key Findings

The analysis provides several useful observations about the Amazon Prime content dataset.

### ⭐ Ratings

IMDb scores are concentrated mainly in the mid-to-high rating range, with a substantial amount of content receiving ratings around **6–8**.

### 📅 Release Trends

The dataset shows significant growth in content releases after **2010**, with particularly strong growth during the later years.

### ⏱️ Runtime

Runtime does not show a strong relationship with IMDb ratings, suggesting that longer content does not necessarily receive higher ratings.

### 👨‍👩‍👧 Family & Kids Content

Family and kids-oriented content provides an interesting category for further analysis because of its comparatively strong rating patterns.

### 🌎 Production Countries

The dataset contains content from multiple countries, including international and multi-country productions.

### 👤 Actors

Actor analysis shows a long-tail pattern where a smaller number of actors appear in many titles while a large number of actors appear in relatively fewer titles.

### ⭐ IMDb Votes

IMDb vote counts vary considerably across titles, with popular content receiving substantially more votes than less-known titles.

---

# 💼 Business Insights

The analysis can help streaming platforms understand:

* Which content categories attract audiences
* How content production has changed over time
* Which genres and audience categories deserve further investigation
* How ratings vary across different content characteristics
* How geographical content distribution differs
* Which factors may be useful for recommendation and personalization systems

---

# 🚀 Future Scope

This EDA project can be extended into a complete data science project by:

### 🤖 Recommendation System

Build a recommendation system based on:

* Genre
* Ratings
* Actors
* Country
* Content similarity

### 📊 Interactive Dashboard

Create an interactive dashboard using:

* Power BI
* Tableau
* Streamlit

### 🧠 Machine Learning

Develop models for:

* Rating prediction
* Popularity prediction
* Content classification

### 📝 NLP

Apply Natural Language Processing to:

* Show descriptions
* Genre information
* Content similarity
* Text-based recommendation

---

# 📁 Project Structure

```text
Amazon-Prime-TV-Shows-Exploratory-Data-Analysis/
│
├── Amazon_Prime_TV_Shows_EDA.ipynb
├── README.md
│
└── dataset/
    ├── titles.csv
    └── credits.csv
```

---

# ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/meshivammishra/Amazon-Prime-TV-Shows-Exploratory-Data-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Amazon-Prime-TV-Shows-Exploratory-Data-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open the notebook

```bash
jupyter notebook
```

Then open:

```text
Amazon_Prime_TV_Shows_EDA.ipynb
```

---

# 👨‍💻 Project Information

**Project Title:** Amazon Prime TV Shows – Exploratory Data Analysis

**Project Type:** Exploratory Data Analysis (EDA)

**Contribution:** Individual

**Author:** Shivam Mishra

---

## 📌 Skills Demonstrated

* Python
* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis
* Pandas
* NumPy
* Data Visualization
* Matplotlib
* Seaborn
* Statistical Analysis
* Data Interpretation
* Business Insights

---

## ⭐ Conclusion

This project demonstrates the complete process of performing **Exploratory Data Analysis using Python**, starting from data inspection and cleaning to visualization and insight generation.

The analysis provides a better understanding of Amazon Prime's content library and demonstrates how data can be transformed into meaningful insights for decision-making.

---

### 👤 Author

**Shivam Mishra**

📌 Data Science | Python | SQL | Power BI | Machine Learning

⭐ If you find this project useful, consider giving the repository a star.
