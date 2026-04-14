# Netflix-Exploratory-Data-Analysis-

# 🎬 Netflix Content Analysis (EDA Project)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix dataset to uncover insights about content trends, distribution, and growth over time.

The goal is to transform raw data into meaningful insights that can help understand:

* Content distribution (Movies vs TV Shows)
* Growth of Netflix content over the years
* Country-wise production trends
* Popular genres and ratings

---

## 📂 Dataset

* Source: Kaggle Netflix Dataset
* Contains information about:

  * Title, Type (Movie/TV Show)
  * Director, Cast
  * Country
  * Date Added
  * Release Year
  * Rating
  * Duration
  * Genre

---

## 🛠️ Tools & Technologies

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Cleaning

* Handled missing values (director, cast, country)
* Converted date columns into datetime format
* Removed inconsistent or null records

### 2. Feature Engineering

* Extracted:

  * Year Added
  * Month Added
* Created new features for time-based analysis

### 3. Exploratory Data Analysis (EDA)

* Distribution of Movies vs TV Shows
* Content growth over time
* Top producing countries
* Ratings distribution
* Genre analysis

---

## 📊 Key Insights

* 🎥 **Movies dominate Netflix content** compared to TV Shows
* 📈 **Rapid growth after 2015**, showing platform expansion
* 🌍 **United States produces the highest content**
* ⭐ Majority of content falls under **TV-MA and TV-14 ratings**
* 🎭 Drama and International content are among the most common genres

---

## 📈 Visualizations

The project includes:

* Count plots
* Bar charts
* Time-series analysis
* Heatmaps

---

## 📁 Project Structure

```
📦 netflix-content-analysis
 ┣ 📜 Exploratory-Data-Analysis.ipynb
 ┣ 📜 README.md
 ┗ 📂 dataset
```

---

## 🚀 How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/netflix-content-analysis.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook:

```
jupyter notebook
```

---

## 💡 Future Improvements

* Add interactive dashboards (Power BI / Tableau)
* Perform advanced analysis (correlation, clustering)
* Build recommendation system using ML

---

## 🤝 Contributing

Feel free to fork this repository and improve the analysis.

---

## ⭐ If you found this useful

Give this repo a ⭐ and share your feedback!

---
