
# 🎬 Netflix Data Analysis | Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Titles dataset to uncover meaningful insights about:

- Content growth trends
- Movies vs TV Shows distribution
- Audience targeting
- Genre popularity
- Country-wise production
- Duration analysis

The analysis was conducted using **Python in Jupyter Notebook**, focusing on data cleaning, feature engineering, and visualization.

---

## 🎯 Project Objectives

- Analyze distribution of Movies and TV Shows
- Study yearly content growth on Netflix
- Identify top content-producing countries
- Categorize audience ratings (Kids / Teen / Adult)
- Analyze movie duration and TV show seasons
- Perform feature engineering for deeper insights

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

### ✔ Handling Missing Values
- Filled missing values in:
  - `director`
  - `cast`
  - `country`
- Managed missing dates in `date_added`

### ✔ Feature Engineering
- Converted `date_added` to datetime
- Extracted `added_year`
- Created:
  - `duration_minutes` (for Movies)
  - `seasons` (for TV Shows)
  - `rating_category` (Kids / Teen / Adult)
  - `genre_count`
  - `cast_count`
  - `content_age`

### ✔ Data Standardization
- Cleaned categorical fields
- Removed duplicates
- Structured duration column

---

## 📊 Key Visualizations

### 📌 1. Movies vs TV Shows Distribution
Shows overall content distribution.

### 📌 2. Content Added Over Years
Identifies growth trend of Netflix content.

### 📌 3. Movies vs TV Shows Growth Comparison
Compares yearly addition of Movies and TV Shows.

### 📌 4. Top 10 Content Producing Countries
Highlights major production countries.

### 📌 5. Audience Rating Distribution
Shows target audience segmentation.

### 📌 6. Genre Distribution
Identifies most popular content genres.

### 📌 7. Duration Distribution
Analyzes:
- Movie runtime patterns
- TV show season trends

---

## 📈 Key Insights

- 📈 Significant content growth observed after 2016.
- 🎬 Movies dominate Netflix's content library.
- 📺 TV Shows show consistent growth in recent years.
- 🌎 United States and India are leading content producers.
- 👨‍👩‍👧 Most content targets adult audiences.
- ⏱ Majority of movies range between 90–120 minutes.

---

## 📂 Project Structure

```

Netflix-DataAnalysis/
│
├── Netflix_DataAnalysis.ipynb
├── netflix_titles.csv
├── README.md
└── requirements.txt

````

---

## 🚀 How to Run This Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Netflix-DataAnalysis.git
````

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Netflix_DataAnalysis.ipynb` and run all cells.

---

## 📚 Dataset Source

Netflix Titles Dataset (Kaggle)

---

## 🔮 Future Improvements

* Build interactive dashboard using Streamlit or Plotly
* Deploy dashboard on web
* Perform predictive modeling
* Add advanced statistical analysis
* Perform clustering on content categories

---


## 👨‍💻 Author

**Ritik Raj**
Final Year – Computer Science & Engineering
Aspiring Data Analyst | Machine Learning Enthusiast


