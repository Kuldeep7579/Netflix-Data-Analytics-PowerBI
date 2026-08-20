# Netflix Content Intelligence Dashboard 🎬

An end-to-end data analytics project built using **Python** and **Power BI** to explore Netflix's content catalog. The project covers data cleaning, transformation, DAX calculations, and interactive dashboard development.

## 📌 Project Overview

The Netflix dataset was cleaned and prepared using Python, then imported into Power BI to create an interactive dashboard for analyzing movies, TV shows, ratings, genres, countries, and content trends over time.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Power BI
- DAX
- Git & GitHub

## 📂 Data Cleaning Process

The following steps were performed using Python:

1. Dataset loading and basic inspection
2. Duplicate values check and removal
3. Missing values analysis and handling
4. Conversion of `date_added` to datetime
5. Verification of `release_year`
6. Cleaning of the `country` column
7. Preparation of `listed_in` for genre analysis
8. Cleaning of the `duration` column
9. Creation of `Year Added`, `Month Number`, and `Month Name`
10. Data type correction

## 📊 Dashboard Features

### KPI Cards
- Total Titles
- Total Movies
- Total TV Shows
- Total Countries
- Average Rating

### Visualizations
- Content Added Over Time
- Movies vs TV Shows
- Rating Distribution
- Top Genres
- Top Countries
- Content by Country
- Top 5 Recently Added Titles

### Interactive Filters
- Type
- Rating
- Country
- Genre
- Release Year
- Year Added

A **Clear All Slicers** button is included to reset the dashboard filters.

## 🧮 DAX & Data Modeling

The Power BI dashboard uses calculated columns and measures for metrics such as:

- Total Titles
- Total Movies
- Total TV Shows
- Total Countries
- Average Rating
- Year Added
- Month Number
- Month Name

## 📷 Dashboard Preview

Upload your dashboard screenshot to an `images` folder and use:

```markdown
![Netflix Content Intelligence Dashboard](images/dashboard.png)
```

## 📁 Project Structure

```text
Netflix-Data-Analytics-PowerBI/
│
├── data/
│   ├── netflix_titles.csv
│   └── netflix_cleaned.csv
│
├── notebooks/
│   └── Netflix_Data_Cleaning.ipynb
│
├── dashboard/
│   └── Netflix_Content_Intelligence_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

> Update the file and folder names above according to your actual repository structure.

## 🚀 How to Run

### Python

```bash
git clone https://github.com/Kuldeep7579/Netflix-Data-Analytics-PowerBI.git
cd Netflix-Data-Analytics-PowerBI
pip install pandas
```

Open the Jupyter Notebook and run the data-cleaning steps.

### Power BI

1. Open the `.pbix` file in Power BI Desktop.
2. Load or refresh the cleaned dataset if required.
3. Explore the dashboard using the interactive slicers.
4. Use **Clear Filters** to reset all selections.

## 💡 Key Questions Answered

- How is Netflix content distributed between Movies and TV Shows?
- How has Netflix content grown over time?
- Which countries contribute the most titles?
- Which genres are most common?
- How are titles distributed across ratings?
- Which titles were added most recently?

## 🎯 Skills Demonstrated

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis
- Data Transformation
- Feature Engineering
- Date Analysis
- DAX Calculations
- Power BI Visualization
- Dashboard Design
- Interactive Reporting
- Git & GitHub

## 👤 Author

**Kuldeep Kumar**

GitHub: https://github.com/Kuldeep7579

---

⭐ If you like this project, consider giving the repository a star!
