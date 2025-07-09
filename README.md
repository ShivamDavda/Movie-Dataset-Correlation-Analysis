# 🎬 Movie Dataset Correlation Analysis

This project performs an exploratory correlation analysis on a movie dataset to understand what factors are most associated with a movie's gross revenue. It uses Python for data cleaning, visualization, and statistical analysis.

---

## 📌 Objectives

- Clean and preprocess the movie dataset
- Analyze trends in budget, revenue, ratings, and more
- Identify correlations between numeric and categorical features
- Visualize relationships using heatmaps and regression plots
- Provide actionable insights based on the analysis

---

## 🛠️ Tools & Libraries

- Python
- pandas
- numpy
- seaborn
- matplotlib

---

## 📊 Key Analyses Performed

- **Budget vs Gross Revenue**  
  Linear regression shows a strong positive correlation between budget and gross revenue.

- **Votes vs Gross Revenue**  
  Higher number of votes often links with higher gross earnings.

- **Correlation Heatmaps**  
  Used Pearson, Kendall, and Spearman methods to understand how numerical and categorical factors relate.

- **Top Performing Companies & Years**  
  Identified companies with most high-grossing films and their peak years.

---

## 🔍 Correlation Insights

| Feature Pair            | Correlation Type | Strength     |
|-------------------------|------------------|--------------|
| Budget vs Gross         | Pearson          | Strong +ve   |
| Votes vs Gross          | Pearson          | Moderate +ve |
| Score vs Gross          | Pearson          | Weak +ve     |
| Company vs Gross (cat)  | Factorized       | Varies       |
| Year vs Gross           | Factorized       | Varies       |



