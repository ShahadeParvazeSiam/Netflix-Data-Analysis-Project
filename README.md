# 🎬 Netflix Data Analysis

## 📊 Project Overview  
This project focuses on analyzing and visualizing **Netflix’s movie and TV show dataset** to uncover valuable insights about content distribution, release trends, and audience preferences.  
The main goal was to explore **genre popularity**, **release patterns**, and **country contributions** to Netflix’s global content library.

Using **Python (NumPy, Pandas, Matplotlib, Seaborn)**, I performed data cleaning, transformation, and exploratory data analysis (EDA) to visualize meaningful patterns and summarize key insights.

---

## 🎯 Objectives  
- Explore and clean the Netflix dataset  
- Perform **exploratory data analysis (EDA)** to identify content trends  
- Compare **Movies vs. TV Shows** distribution  
- Visualize country-wise and year-wise trends  
- Derive insights about **genres, ratings, and release years**

---

## 🗂️ Dataset Overview  
The dataset contains detailed information about movies and TV shows available on Netflix.

| Feature | Description |
|----------|--------------|
| `show_id` | Unique ID for each title |
| `type` | Type of content – Movie or TV Show |
| `title` | Name of the title |
| `director` | Director of the title |
| `cast` | Main cast members |
| `country` | Country where the content was produced |
| `date_added` | Date when the content was added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating (e.g., TV-MA, PG-13, etc.) |
| `duration` | Duration of the title (in minutes or seasons) |
| `listed_in` | Genre or category |
| `description` | Brief summary of the title |

---

## 🧹 Data Cleaning  
- Removed duplicate records and handled missing values  
- Converted date columns to proper datetime format  
- Extracted **year, month**, and **content type** for trend analysis  
- Standardized categorical data for consistent grouping  
- Ensured all numerical fields were properly typed  

---

## 🔍 Exploratory Data Analysis (EDA)

### 💡 Key Insights  
- **Movies** make up the majority of Netflix content compared to TV Shows  
- **United States** and **India** are the leading content-producing countries  
- Significant growth in Netflix content was observed after **2015**  
- The most popular **genres** include *International Movies*, *Dramas*, and *Comedies*  
- Most titles are released or added during the **last quarter of the year**

---

## 📈 Visualizations  
- Movies vs. TV Shows comparison charts  
- Yearly trend of content added to Netflix  
- Country-wise content distribution heatmap  
- Genre frequency analysis  
- Rating and duration insights  

> All visualizations were built using **Matplotlib** and **Seaborn** for clear and professional presentation.

---

## 🧭 Tools & Libraries Used  
- 🐍 **Python 3.x**  
- 🔢 **NumPy** – numerical computations  
- 🧮 **Pandas** – data manipulation and cleaning  
- 📊 **Matplotlib** & **Seaborn** – visualization and EDA  

---

## 🚀 Results & Insights  
- Netflix content has expanded rapidly in the past decade  
- Certain genres and countries dominate the platform’s catalog  
- The majority of Netflix’s content is movie-based, reflecting audience demand  
- Yearly addition trends indicate Netflix’s aggressive content expansion strategy  

---

## 💡 What I Learned  
- Improved understanding of **EDA and data storytelling**  
- Strengthened skills in **data visualization** and **insight interpretation**  
- Learned to handle **missing data**, **categorical variables**, and **time-based analysis** effectively  

---

## 🔮 Future Enhancements  
- Develop an **interactive dashboard** using **Plotly** or **Power BI**  
- Perform **sentiment analysis** on title descriptions  
- Add **recommendation system insights** using similarity metrics  
- Automate data updates via Netflix API (if available)  

---


## 📁 Project Structure

└── Netflix_Data_Analysis/
    ├── Python_Project_2_Netflix.ipynb    # Jupyter Notebook (EDA & Visualization)
    ├── netflix_titles.csv                # Dataset
    └── README.md                         # Project Documentation


