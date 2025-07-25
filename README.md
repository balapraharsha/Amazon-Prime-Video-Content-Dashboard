# 📊 Amazon Prime Video Content Dashboard – Power BI

This interactive Power BI dashboard provides a comprehensive analysis of Amazon Prime Video's content library. It explores trends, genres, country-wise contributions, ratings, and more to uncover insights.

---

## 📁 Dataset Overview

The dataset includes metadata of Amazon Prime content such as:

| Column             | Description                               |
|--------------------|-------------------------------------------|
| `show_id`          | Unique ID of the show                     |
| `type`             | Movie or TV Show                          |
| `title`            | Title of the content                      |
| `director`         | Director(s) name                          |
| `cast`             | Main actors in the content                |
| `country`          | Country of production                     |
| `release_year`     | Year of original release                  |
| `rating`           | Maturity rating (e.g., PG, TV-MA)         |
| `duration`         | Original format (minutes or seasons)      |
| `listed_in`        | Genre(s)                                  |
| `description`      | Short summary of the content              |
| `date_added`       | Date it was added to Amazon Prime         |
| `duration_in_min`  | Standardized duration in minutes (created) |

---

## 📌 Key Features

- ✅ Cleaned & standardized `duration` column (mins + seasons → unified as minutes)
- ✅ Null handling for `date_added` and `rating`
- ✅ Categorized and visualized genres, ratings, and countries
- ✅ KPI cards, charts, and custom insights
- ✅ Built using **Power BI Desktop**

---

## 📊 Visualizations Included

- 📆 **Content release trend** over years
- 🎥 **Movies vs TV Shows** share
- 🌍 **Top countries** contributing content
- 🎭 **Most popular genres**
- ⭐ **Rating distribution**
- ⏱️ **Duration analysis** (standardized in minutes)
- 🔍 **Detailed table explorer** with slicers and filters
- 🧠 **Insights & Recommendations** section

---

## 📈 Insights Summary

- Over **80%** of the content is **Movies**
- **Drama**, **Action**, and **Comedy** are top genres
- Content mostly from **USA** and **India**
- Content rated **13+** dominates; minimal kids/family content
- Huge content growth observed **post-2015**

---

## 🛠️ Tools Used

- **Power BI Desktop**
- Power Query (M Language) for data cleaning
- DAX for measures & calculated columns
- GitHub for versioning and sharing

---

## 👨‍💻 Developed By

**Bala Praharsha .M**  
📧 [balapraharsha.m@gmail.com]  
🔗 [LinkedIn](https://linkedin.com/in/mannepalli-bala-praharsha) | [GitHub](https://github.com/balapraharsha)

---

## 📂 Repository Structure

```bash

📁 Amazon-Prime-Dashboard
├── Prime_Dashboard.pbix # Power BI project file
├── Prime_Dashboard.pdf # PDF export of dashboard
├── sample_data.csv # dataset
└── README.md # Project overview

```

---

## ⭐ If you like this project, give it a ⭐ and feel free to fork or contribute!
