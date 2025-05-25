# 🎬 Netflix Movies and TV Shows Data Analysis

A data analysis project exploring Netflix's content library using **Python**, **Pandas**, and **visualization libraries** like **Seaborn** and **Matplotlib**.

## 📁 Dataset

- **Source**: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File Used**: `netflix_titles.csv`
- The dataset contains information on Netflix Movies and TV Shows available up to 2021.

## 🎯 Project Objectives

This project aims to explore and analyze Netflix's content to answer the following questions:

1. What’s the distribution between movies and TV shows?
2. Which countries have the most Netflix content?
3. How has the number of Netflix releases changed over the years?
4. What are the most common genres on Netflix?

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- Jupyter Notebook 

## 🧹 Data Cleaning Steps

- Converted `date_added` to `datetime` format
- Extracted `year_added` and `month_added`
- Filled or dropped missing values where appropriate
- Split and analyzed multi-label genre fields

## 📊 Key Visualizations

- Bar plot of Movies vs TV Shows
- Line chart of content added over the years
- Bar chart of top contributing countries
- Frequency chart of top genres

## 💡 Key Insights

- Netflix has significantly more movies than TV shows.
- The USA dominates Netflix’s content library.
- Content additions peaked around 2019–2020.
- Common genres include **Dramas**, **International Movies**, and **Comedies**.

## 📌 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
