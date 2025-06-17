# 📊 Netflix Global Content Trends (2016–2021)

🎬 **Uncovering the Data Behind the Drama**  
A data analytics project that dives deep into Netflix’s global content catalog using Python and Power BI. This project explores what the world has been watching — and how Netflix's streaming strategy evolved from 2016 to 2021.

---

## 🚀 Project Overview

This project aims to analyze, visualize, and extract insights from Netflix's publicly available titles dataset. It combines **Exploratory Data Analysis (EDA)** in Python with a rich, interactive **Power BI dashboard** to tell the story behind Netflix's content expansion, genre diversity, country-wise contributions, and user-oriented classifications.

---

## 🔍 Objectives

- Understand the split between Movies vs TV Shows
- Identify top genres, most common age ratings, and content duration patterns
- Analyze content release and addition trends over time
- Highlight global content contribution by country
- Create a business-friendly dashboard using Power BI

---

## 📁 Project Structure
netflix-global-content-trends/
│
├── data/
│ └── cleaned_netflix_dataset.csv # Cleaned and enriched dataset
│
├── eda/
│ ├── Netflix_EDA_Summary_DeepaNayak.pdf # Final EDA report with insights
│ └── notebook.ipynb # Python notebook (optional)
│
├── dashboard/
│ ├── Netflix_Dashboard.pbix # Power BI dashboard (source file)
│ └── Netflix_Dashboard.pdf # Exported view of final dashboard
│
└── README.md # Project documentation


---

## 🧠 Tools & Technologies

| Tool         | Purpose                              |
|--------------|--------------------------------------|
| Python       | Data cleaning and EDA                |
| Pandas       | Data manipulation                    |
| Matplotlib & Seaborn | Data visualization (EDA)    |
| Power BI     | Interactive dashboard and storytelling |
| Jupyter Notebook | Code & insight documentation     |

---

## 📊 Key Visual Insights

- 🔢 Total Titles: 8,807 (Movies & TV Shows)
- 🌍 Countries with most content: USA, India, UK, South Korea
- 🏷️ Top Genres: Dramas, Comedies, Documentaries
- 🔞 Most Common Ratings: TV-MA, TV-14, PG-13
- 📈 Peak Release Year: 2019
- 📅 Content spike observed post-2016 with gradual diversification

---

## 📌 Dashboard Preview

👉 Explore the Power BI dashboard here (PDF):  
[📄 Netflix Global Dashboard (PDF)](./dashboard/Netflix_Dashboard.pdf)

🧠 It includes slicers for content type, country, release year, and interactive visuals for:
- Genre breakdown
- Year-wise additions
- Ratings distribution
- Country-wise content counts
- KPIs (Movies, Shows, Oldest Title, Top Country, etc.)

---

## 📦 Dataset

- **Source:** [Kaggle – Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Last updated: 2021
- Fields include: `title`, `type`, `director`, `cast`, `country`, `release_year`, `date_added`, `duration`, `rating`, `listed_in`, etc.

---

## 🧹 Data Cleaning Summary

- Handled missing values in `director`, `cast`, `country`, `rating`, `duration`
- Converted `date_added` to datetime
- Created new fields: `year_added`, `month_added`
- Exploded multi-value fields for genre and country analysis

---

## 📝 Key Learnings

- Hands-on EDA and preprocessing techniques
- Dashboard storytelling with business-ready KPIs
- Visual filtering, chart optimization, and layout design in Power BI
- Building a data project end-to-end, from raw CSV to executive dashboard

---

## 💼 Author

**Deepa Nayak**  
🔗 [LinkedIn](https://www.linkedin.com/in/deepa-nayak-a825a7175)  
💻 [GitHub Portfolio](https://github.com/Deepanayaktangodu)

---

## ⭐ If you found this helpful, please consider giving the repo a star!



