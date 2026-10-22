# Music Store Sales Analysis

## Project Overview
This project analyzes the sales and customer data of an online music store using SQL. The goal is to extract business insights, understand customer behaviors, and identify sales trends from a relational database.

---

## Tools & Technologies
- **Database:** PostgreSQL
- **Database Management Tool:** PgAdmin4
- **Data Source:** Music store database (schema provided below, data in `music store data.zip`)
- **Analysis Method:** SQL queries (see `music_database_analysis.sql`)

---

## Database Schema
The database schema models a typical music store, with tables such as:
- `employee`
- `customer`
- `invoice`
- `invoice_line`
- `track`
- `album`
- `artist`
- `genre`

Refer to `Music_Database_Schema.png` for the full ER diagram.

---

## Project Workflow

1. **Database Setup:**
   - Load the schema and data into PostgreSQL using PgAdmin4.
   - Ensure all tables and relationships are correctly established.

2. **Exploratory Analysis:**
   - Use SQL queries to explore the data, such as counting records, checking for nulls, and understanding distributions.

3. **Business Question Formulation:**
   - The queries in `music_database_analysis.sql` are designed to answer real-world business questions relevant to a music store.

4. **Query Execution & Results Interpretation:**
   - Run each query, analyze the results, and interpret them in a business context (e.g., who are the best customers, which genres are most popular).

5. **Reporting & Visualization (Optional):**
   - Results can be exported for reporting or visualization in tools like Excel, Tableau, or Power BI.

---

## Analysis & Key Queries
The analysis is organized into sets of business questions:

### Query Set 1: General Business Insights
- **Q1:** Who is the senior most employee based on job title?
- **Q2:** Which countries have the most invoices (sales)?
- **Q3:** What are the top 3 invoice totals (biggest sales)?
- **Q4:** Which city has the highest total sales?
- **Q5:** Who is the best customer (highest spender)?

### Query Set 2: Customer and Music Preferences
- **Q1:** List all customers who listen to Rock music, ordered by email.
- **Q2:** Find the top 10 artists with the most Rock tracks.
- **Q3:** List tracks longer than the average song length.

### Query Set 3: Advanced Sales Analysis
- **Q1:** Calculate how much each customer has spent on each artist.

See `music_database_analysis.sql` for the full SQL code and logic.

---

## Significance & Business Value
- **Customer Insights:** Identify top customers, their preferences, and spending habits.
- **Sales Trends:** Reveal which countries, cities, and genres are most profitable.
- **Artist Analysis:** Show which artists are most popular and generate the most revenue.
- **Operational Decisions:** Help in planning promotions, events, and targeted marketing (e.g., city for a music festival).

---

## Learning Outcomes
- Advanced SQL querying (joins, aggregations, subqueries, CTEs)
- Business data analysis
- Relational database schema design

---

## Potential Extensions
- **Automated Dashboards:** Integrate with BI tools for live dashboards.
- **Deeper Analytics:** Predictive modeling for customer churn or sales forecasting.
- **Data Cleaning:** Add scripts for data quality checks and cleaning.

---

## Summary Table
| Aspect                | Details                                                                 |
|-----------------------|-------------------------------------------------------------------------|
| **Domain**            | Online Music Store Sales & Customer Analytics                           |
| **Tech Stack**        | PostgreSQL, PgAdmin4, SQL                                               |
| **Key Outputs**       | Top customers, sales by country/city, popular genres/artists, etc.      |
| **Business Impact**   | Informs marketing, sales, and operational decisions                     |
| **Learning Outcome**  | Advanced SQL querying, business data analysis, relational schema design |

---

## References
- See `Music_Database_Schema.png` for schema
- See `music_database_analysis.sql` for all queries
- Data: `music store data.zip`

---

## Schema- Music Store Database
![Music_Database_Schema](https://github.com/Mradul-mg/SQL-music-store-analysis/assets/81468832/c7b7894e-f14d-4deb-bd32-730a355d009d)


