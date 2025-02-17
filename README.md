# sakila-db-exercises
# 🎬 Sakila Dataset Analysis with SQL Workbench

![image](https://github.com/user-attachments/assets/063dba7a-2867-4296-8cbe-9deba696cd74)

Welcome to the **Sakila Dataset Analysis** project! In this project, I worked with the **Sakila** dataset, a popular database used to represent a video rental system. I analyzed the dataset using **SQL Workbench** to extract meaningful insights about customers, films, rentals, and store performance.

## 📊 Project Overview

The **Sakila** dataset includes various tables that store information such as:

- **Films** 🎥
- **Customers** 👥
- **Rentals** 📅
- **Staff** 👨‍💼
- **Stores** 🏢
- **Payments** 💳
- **Categories** 🎬

The goal of this analysis was to query the database using SQL to explore the relationships between these tables and uncover key business insights like popular films, customer rental behavior, and store performance.

## 🛠️ Tools and Techniques Used

### SQL Workbench Features Utilized:
- **SQL Queries** 📝: Wrote SQL queries to retrieve specific data from the Sakila database, such as customer rental history, total payments, and film popularity.
- **Joins** 🔗: Utilized INNER JOINs and LEFT JOINs to combine data from multiple tables (e.g., joining `rentals` with `films` to find which films were rented the most).
- **Aggregation Functions** 📊: Used aggregation functions like `SUM()`, `COUNT()`, `AVG()` to compute totals, averages, and counts such as total rental payments, rental count, etc.
- **Group By** 🧑‍🤝‍🧑: Grouped data by categories like film type, customer, or store to identify trends and patterns.
- **Subqueries** 🔍: Applied subqueries for more complex filtering and retrieving results based on conditions from other queries.

### Key Insights & Analysis:
- **Popular Films** 🎥: Identified the top-performing films based on rental frequency.
- **Customer Rental Patterns** 👥📅: Analyzed customer rental history and determined which customers rented the most films.
- **Store Performance** 🏢💳: Evaluated store performance by analyzing total payments and rentals for each store.
- **Payment Trends** 💳📊: Investigated payment trends and the average payment amount per customer.
- **Category-wise Film Analysis** 🎬: Examined which film categories (e.g., Action, Drama) generated the most rentals and revenue.

## 🖼️ Project Visuals

Here are some SQL queries:
/* 1) Display the first and last names of all actors from the table actor*/
select first_name, last_name
from actor;

/* 2) You need to find the ID number, first name, and last name of an actor, of whom you know only the first name, “Joe.” 
What is one query would you use to obtain this information? */
select actor_id, first_name, last_name
from actor
where first_name = 'joe';

/* 3) Select specific columns from the films table that last 3 hours or longer. */    
select length
from film
order by length desc;

## 🚀 How to Use

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/Sakila-Analysis.git
    ```

2. Open the SQL scripts in **SQL Workbench** or any other SQL-compatible tool.

3. Execute the SQL queries to explore the Sakila dataset and gather insights.

4. Customize or extend the queries to explore additional analysis or answer your own business questions.

## 📈 Conclusion

This project demonstrates how SQL can be used to analyze a complex relational database like Sakila, providing insights into customer behavior, store performance, and film popularity. By using joins, aggregation functions, and subqueries, I was able to extract valuable business intelligence from the data, which could help optimize inventory, improve customer service, and enhance sales strategies.

## 💬 Feedback & Contributions
ChatGPT
Feel free to open issues or submit pull requests if you have any suggestions, improvements, or feedback. Contributions are welcome!

---

Thank you for checking out the **Sakila Dataset Analysis** project! 🎬📊
