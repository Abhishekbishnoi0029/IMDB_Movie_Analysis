# IMDB Movie Analysis using Python

## 📌 Project Overview  
This project focuses on analyzing the **IMDB Movies dataset** to uncover insights into movie trends, genre popularity, and the factors influencing movie success. Using **Python** and powerful libraries like **Pandas, NumPy, Matplotlib, and Seaborn**, we explore patterns in ratings, revenue, and other attributes to answer key business questions.

---

## 📂 Dataset Information  
The dataset contains various attributes of movies such as:
- 🎥 **Movie Title** (`Series_Title`)
- 🎭 **Genre** (`Genre`)
- 📆 **Release Year** (`Released_Year`)
- ⭐ **IMDB Rating** (`IMDB_Rating`)
- 🏆 **Meta Score** (`Meta_score`)
- 💰 **Revenue (Gross Earnings)` (`Gross`)
- ⏳ **Runtime** (`Runtime`)
- 🎬 **Director & Cast** (`Director`, `Star1`, `Star2`, etc.)

Each row represents one movie, and we analyze the dataset to derive meaningful insights.

---

## 🚀 Steps in Analysis  

### 1️⃣ Data Preprocessing & Cleaning  
✔ Checked for **missing values** in `Meta_score`, `Gross`, and `Released_Year`.  
✔ Converted `Released_Year` to **numeric format**.  
✔ Replaced missing values with appropriate statistics (mean, median).  
✔ Identified and removed **outliers** in revenue data using boxplots.  
✔ Converted categorical data (e.g., `Genre`) into useful formats.  

---

### 2️⃣ Exploratory Data Analysis (EDA)  

#### 📌 **Univariate Analysis** (Single Variable Analysis)  
✔ **IMDB Ratings Distribution** → Used **Histogram** to analyze how movie ratings are distributed.  
✔ **Top Genres** → Used **Bar Charts** to identify the most common movie genres.  
✔ **Revenue Distribution** → Used **Boxplots** to detect outliers in revenue data.  

#### 📌 **Bivariate Analysis** (Relationship Between Two Variables)  
✔ **Budget vs. Revenue** → Used **Scatter Plots** to check correlation.  
✔ **Ratings vs. Revenue** → Checked how ratings impact revenue.  
✔ **Country vs. Ratings** → Used **Boxplots** to compare IMDB ratings across different countries.  

#### 📌 **Multivariate Analysis** (Multiple Variable Analysis)  
✔ **Correlation Between Revenue, Budget, and Ratings** → Used **Heatmaps** to find strong correlations.  
✔ **Genre vs. Year vs. Ratings** → Visualized the evolution of genre popularity over time.  

---

## 📊 Key Insights & Findings  
✅ **High-budget movies tend to earn higher revenue.**  
✅ **Action and Sci-Fi genres are the most financially successful.**  
✅ **Movies from the 1990s and 2000s have the highest average IMDB ratings.**  
✅ **Meta Score and IMDB Ratings show a positive correlation.**  
✅ **Movies with longer runtimes tend to have slightly better ratings.**  

---

## 📌 Technologies Used  
🔹 **Python** 🐍  
🔹 **Pandas & NumPy** → Data Cleaning & Manipulation  
🔹 **Matplotlib & Seaborn** → Data Visualization  
🔹 **Jupyter Notebook** → For writing and running analysis  

---
## 📢 Conclusion  
This project provides **valuable insights into IMDB movies**, helping us understand **trends in ratings, genres, and revenue**.  
If you found this useful, ⭐ **star the repository** and contribute! 🚀  

---

### 📬 Connect with Me    
🔗 **LinkedIn:** [linkedin.com/in/your-profile](www.linkedin.com/in/abhishek-bishnoi-769baa2a8)  

---

### ✅ **Next Steps (Future Scope)**  
📌 Analyze the impact of **directors, actors, and production studios** on movie success.  
📌 Investigate **geographic trends** in movie ratings and revenue.  
📌 Examine how **runtime affects audience satisfaction and ratings**.  

