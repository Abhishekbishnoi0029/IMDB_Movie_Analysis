# 🎬 IMDB Movie Analysis using Python  

## 📌 Project Overview  
This project aims to analyze the **IMDB Top 1000 Movies dataset** using Python and its powerful libraries like **Pandas, NumPy, Matplotlib, and Seaborn**. Through **Exploratory Data Analysis (EDA)**, we uncover patterns in movie trends, ratings, genres, and financial success.  

## 📂 Dataset Information  
- **Source:** IMDB Top 1000 Movies Dataset  
- **Key Attributes:**  
  - 🎥 **Movie Title** (`Series_Title`)  
  - 🎭 **Genre** (`Genre`)  
  - 📆 **Release Year** (`Released_Year`)  
  - ⭐ **IMDB Rating** (`IMDB_Rating`)  
  - 🏆 **Meta Score** (`Meta_score`)  
  - 💰 **Revenue (Gross Earnings)** (`Gross`)  

---

## 🚀 Steps in Analysis  

### 1️⃣ Data Preprocessing & Cleaning  
✔ Handled **missing values** (especially in `Meta_score` and `Gross`).  
✔ Converted `Released_Year` to **numeric format**.  
✔ Identified and removed **outliers** in revenue data.  

### 2️⃣ Exploratory Data Analysis (EDA)  
✔ **Univariate Analysis** → Understanding individual columns (e.g., **IMDB ratings distribution** using **histogram**).  
✔ **Bivariate Analysis** → Relationship between two variables (e.g., **Budget vs Revenue using scatter plot**).  
✔ **Multivariate Analysis** → Correlation between multiple variables (**Heatmap**).  

### 3️⃣ Data Visualization  
✔ **Histogram** → Distribution of movie ratings.  
✔ **Boxplot** → Detecting outliers in revenue.  
✔ **Scatter Plot** → Relationship between revenue & ratings.  
✔ **Heatmap** → Correlation between different features.  

### 4️⃣ Insights & Findings  
✅ **High-budget movies tend to have better revenue**.  
✅ **Action and Sci-Fi genres perform best financially**.  
✅ **Movies from the 1990s and 2000s have the highest IMDB ratings**.  
✅ **Strong correlation between Meta Score and IMDB Rating**.  

---

## 📌 Technologies Used  
🔹 **Python** 🐍  
🔹 **Pandas & NumPy** (Data Cleaning & Manipulation)  
🔹 **Matplotlib & Seaborn** (Data Visualization)  
🔹 **Jupyter Notebook** (For Analysis)  

---

## 📊 Sample Visualizations  
### 🎥 IMDB Rating Distribution  
![IMDB Ratings](https://github.com/Nagar2nd/IMDB-Movie-Analysis-Python/blob/main/images/imdb_rating_distribution.png)  

### 💰 Revenue vs IMDB Rating  
![Revenue vs Rating](https://github.com/Nagar2nd/IMDB-Movie-Analysis-Python/blob/main/images/revenue_vs_rating.png)  

---

## 📎 How to Run This Project?  
1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/Nagar2nd/IMDB-Movie-Analysis-Python.git
