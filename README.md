# Netflix Movies & TV Shows Analysis

## 📌 Project Overview

This project analyzes the Netflix Movies and TV Shows dataset to explore how Netflix's content catalogue has changed over time.

The main question explored in this project is:

**Which years did Netflix add the most content, and what kind of content was added?**

The project follows a complete data analysis workflow, including data inspection, cleaning, exploration, visualization, and interpretation of results.

---

## 🎯 Objectives

- Identify the years when Netflix added the most content.
- Compare the number of Movies and TV Shows.
- Analyze how Netflix's content additions changed over time.
- Practice a complete data analysis workflow using Python.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains **8,807 Netflix titles** and **12 columns**, including information such as:

- Title
- Content type (Movie or TV Show)
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Genre
- Description

---

## 🧹 Data Cleaning

The main cleaning steps included:

- Converting `date_added` from text to datetime format.
- Creating a new `year_added` column.
- Checking missing values.
- Verifying that the date conversion was successful.
- Preparing the relevant columns for analysis.

---

## 📈 Analysis & Visualizations

The project explores:

### 1. Netflix Titles Added Each Year

The number of titles added to Netflix increased significantly after 2015.

The highest number of titles was added in **2019**, with **2,016 titles** added to the catalogue.

### 2. Movies vs TV Shows

The dataset contains:

- **6,131 Movies**
- **2,676 TV Shows**

Movies represent the majority of titles in the dataset.

### 3. Movies and TV Shows Added Over Time

Both Movies and TV Shows increased significantly after 2015.

Movie additions reached their highest level in 2019, while TV Show additions also increased considerably over time.

---

## 💡 Key Findings

- Netflix's catalogue expanded rapidly after 2015.
- **2019 was the peak year**, with the largest number of titles added.
- Movies make up the majority of the Netflix catalogue.
- TV Shows became an increasingly important part of the catalogue over time.
- The period between **2016 and 2019** showed particularly strong catalogue growth.

---

## 📂 Project Structure

```text
netflix-data-analysis/
│
├── Netflix_Movies_TV_Shows_Analysis.ipynb
├── netflix_titles.csv
└── README.md
