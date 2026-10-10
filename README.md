# LEGO Video Games Relational Database & Analytics

A normalized relational SQLite database modeling video game releases, development studios, publishing companies, hardware platforms, and review scores across 30+ LEGO titles.

## 🛠️ Tech Stack
- **Database:** SQLite3
- **Query Language:** SQL
- **Data Formats:** JSON, SQL DDL/DML, CSV

## 📊 Database Schema
- `Games`: Primary catalog tracking game titles, genres, release years, review scores, and foreign keys.
- `Developers`: Studio metadata including year founded and headquarters location.
- `Publisher`: Publishing entities and founding years.
- `Platforms`: Hardware platforms (PC, PlayStation, Xbox, Switch) and platform owners.

## 🔍 Analytical Queries Included
- Multi-table `INNER JOIN` and `LEFT JOIN` operations mapping cross-platform availability.
- Studio and publisher output summaries using `GROUP BY` and `COUNT()`.
- Critical review metric computations utilizing `AVG(reviewScores)`.