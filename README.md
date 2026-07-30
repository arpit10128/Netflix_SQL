## 🎬 Netflix SQL Data Analysis

A SQL project that analyzes Netflix's Movies and TV Shows dataset to uncover meaningful insights about content distribution, ratings, release trends, countries, and genres.

---

## 📖 Overview

This project explores the Netflix Titles dataset using SQL. The objective is to answer real-world business questions by writing SQL queries that analyze different aspects of Netflix's content library.

The analysis focuses on understanding content trends, audience ratings, geographical distribution, release patterns, and content categorization.

---

## 🎯 Objectives

- Analyze the distribution of Movies and TV Shows.
- Identify the most common content ratings.
- Explore content based on release years, countries, and durations.
- Analyze genre distribution using the `listed_in` column.
- Categorize content using keywords from titles and descriptions.
- Solve business problems using SQL queries.

---

## 🗂️ Dataset

This project uses the **Netflix Movies and TV Shows** dataset from Kaggle.

**Dataset Link:**  
https://www.kaggle.com/datasets/shivamb/netflix-shows

---

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- pgAdmin 4

---

## 📊 Business Questions Solved

Some of the SQL problems solved in this project include:

1. Count the number of Movies vs TV Shows.
2. Find the most common rating for movies and TV shows.
3. List all movies released in a specific year (e.g., 2020).
4. Find the top 5 countries with the most content on Netflix.
5. Identify the longest movie.
6. Find content added in the last 5 years.
7. Find all the Movies/TV Shows by director 'Rajiv Chilaka'.
8. List all TV Shows with more than 5 seasons.
9. Count the number of content items in each genre.
10. Find each year and the average numbers of content release in India on Netflix. Return the top 5 years with the highest average content release.
11. List all movies that are documentaries.
12. Find all content without a director.
13. Find how many movies actor 'Salman Khan' appeared in the last 10 years.
14. Find the top 10 actors who have appeared in the highest number of movies produced in India.
15. Categorize the content based on the presence of the keywords 'kill' and 'violence' in the description field. Label content containing these keywords as 'Bad' and all other content as 'Good'. Count how many items fall into each category.

---

## 📈 Key Findings

- Movies significantly outnumber TV Shows on Netflix.
- TV-MA and TV-14 are among the most common content ratings.
- The United States contributes the largest amount of Netflix content.
- Content production increased rapidly after 2015.
- Drama and International Movies are among the most common genres.
- Keyword analysis helps identify documentary, crime, and family-oriented content.

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/netflix-sql.git
```

### Create the database

```sql
CREATE DATABASE netflix_db;
```

### Import the dataset

- Create the table using `create_table.sql`
- Import `netflix_titles.csv`
- Run the SQL queries from `analysis_queries.sql`

---

## 📌 Sample Analysis

- Content distribution by type
- Most common ratings
- Top producing countries
- Release year trends
- Genre analysis
- Duration analysis
- Keyword-based categorization

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

## ⭐ If you found this project useful, consider giving it a star!
