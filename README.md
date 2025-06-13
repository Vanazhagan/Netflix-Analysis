# 🎬 Netflix IMDb Ratings Dashboard (Power BI)

This project presents a comprehensive and visually engaging **Netflix IMDb Ratings Dashboard** built in **Power BI**. The dashboard explores over 5,000 titles on Netflix, segmented by Movies and TV Shows, analyzing IMDb ratings, votes, and genre-based patterns across different countries.

## 📁 Project Overview

- **Project Title**: Netflix IMDb Ratings Dashboard  
- **Tool Used**: Microsoft Power BI  
- **Dataset Source**: IMDb and Netflix titles metadata  
- **Data Size**: 5,603 titles (Movies + TV Shows)  
- **Author**: [Vanazhagan](#contact)

---

## 📊 Key Dashboard Features

### 🔹 KPIs

| Metric               | Value          |
|----------------------|----------------|
| Total Titles         | 5,603          |
| Movies               | 2,648          |
| TV Shows             | 2,955          |
| Average Movie Rating | 7.18           |
| Average TV Rating    | 6.12           |
| Total Votes          | 118.6M+        |

### 🔹 Filters and Segmentation

- Filter by:  
  - **Category**: Movies, TV Shows, or both  
  - **Genres**  
  - **Country**  
  - **Rating Group**  

- Visual Slicers:
  - Rating Group Distribution (horizontal bar)
  - Country-wise Statistics (sortable table)

---

## 📈 Visual Components

1. **Bar Chart**:  
   - **Average IMDb Rating by Genre**
   - Overlaid with title count for deeper context

2. **World Map (Bubble Chart)**:  
   - Visualizes countries with the highest average rating and votes
   - Size of bubble based on titles, rating, or votes

3. **Interactive Table**:  
   - Top IMDb-rated titles with:
     - Title
     - Plot Summary
     - Poster (Image)
     - IMDb Rating & Votes

4. **Country Table**:  
   - Displays average rating, vote count, and total titles per country

---

## 📌 Insights Extracted

- **Top Rated TV Shows**: 
  - "Breaking Bad", "Stranger Things", "13 Reasons Why"
- **Highest Rated Movies**: 
  - "Oppenheimer", "John Wick", "Inception"
- **Most Active Countries** (by content): 
  - United States, India, United Kingdom, Canada
- **Genres with Best Ratings**: 
  - Biography, Drama, History, War

---

## 🧠 Skills Demonstrated

- Data transformation and modeling in Power BI  
- DAX measures for votes, averages, and dynamic filtering  
- Custom visuals: cards, bar charts, geo maps, image rendering  
- UI/UX: modern layout, interactivity, and visual storytelling  
- Analytics: Genre-based performance, user rating behavior, country content trends  

---

## 📂 Folder Structure
- Netflix-IMDb-Dashboard/
- │
- ├── Data/ # Cleaned IMDb + Netflix datasets
- ├── Reports/ # Power BI (.pbix) file
- ├── Screenshots/ # Visual preview images
- │ └── netflix-dashboard.png
- └── README.md # Project documentation

---

## 🔧 Possible Future Enhancements

- Add **release year timeline** trends  
- Include **duration or runtime** filters  
- Add **platform comparison** (Amazon Prime, Disney+ etc.)  
- Enable **user sentiment** via reviews text mining (Python + Power BI)  

---
> **Disclaimer**: This dashboard is created for educational and portfolio purposes only. Data is sourced and transformed for visualization practice.
