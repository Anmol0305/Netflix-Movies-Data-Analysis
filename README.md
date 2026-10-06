# 🎬 Netflix Movies Data Analysis

An end-to-end **Exploratory Data Analysis (EDA)** project on movie data using Python.

## 📌 Project Objective

The goal of this project is to explore movie data and identify patterns in:

- Movie genres
- Popularity
- Vote counts
- Vote-average categories
- Release years
- Most and least popular movies

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔎 Analysis Performed

1. Loaded the movie dataset.
2. Inspected rows, columns and data types.
3. Checked duplicate records.
4. Generated descriptive statistics.
5. Converted `Release_Date` into a datetime column.
6. Removed unnecessary columns.
7. Categorized `Vote_Average` into:
   - `not_popular`
   - `below_avg`
   - `average`
   - `popular`
8. Handled missing values.
9. Split multiple genres into individual values.
10. Exploded the Genre column so each row represents one genre.
11. Converted categorical columns to category dtype.
12. Visualized genre distribution.
13. Visualized vote-category distribution.
14. Identified movies with the minimum popularity.
15. Visualized release-date distribution.
16. Summarized the findings.

## 📊 Key Findings

- **Drama** is the most frequent genre in the exploded dataset.
- The dataset contains **19 unique genres**.
- The minimum popularity shown in the analysis is **13.354**.
- The project analysis identifies **2020** as the year with the highest movie count.
- The dataset contains **9,827 original records** before genre explosion and **25,552 rows** after exploding genres.

## 📁 Project Structure

```text
Netflix-Movies-Data-Analysis/
│
├── Netflix_Movies_Data_Analysis.ipynb
├── requirements.txt
├── README.md
├── screenshots/
│   ├── 01_analysis_screenshot.png
│   ├── 02_analysis_screenshot.png
│   └── ...
└── data/
    └── mymoviedb.csv   # Add your original CSV here
```

## ▶️ How to Run

1. Install Python and Jupyter Notebook.
2. Clone/download this repository.
3. Open `Netflix_Movies_Data_Analysis.ipynb`.
4. The original `mymoviedb.csv` dataset is already included in the `data` folder.
5. Run the notebook from top to bottom.

## 📸 Project Screenshots

The `screenshots` folder contains the screenshots supplied from the completed Jupyter project as supporting documentation.

## 👩‍💻 Skills Demonstrated

**Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | EDA | Data Visualization | Data Transformation**

---
### Author
**Sonali Sharma**
