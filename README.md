# Sparkify ETL

## Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. They'd like a data engineer to create a Postgres database with tables designed to optimize queries on song play analysis.


## Author

- [@Mohamed S. Elaraby](https://github.com/Aboalarbe)


## Role Description

We will create a database schema using Postgers and ETL pipeline using python for this analysis. We will define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from JSON files in two local directories into these tables in Postgres using Python and SQL. we 'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.


## How to run the Python scripts

you should install psycopg2 package

```bash
pip install psycopg2
```

```bash
open CMD and run python create_tables.py
```

```bash
after that run python etl.py
```
    
## Description of files in the repository

### data
contains log_data and song_data which contains JSON files that we will extract the data from (our Data source).

### create_tables.py
contains scripts for creating the DB and Tables.

### etl.ipynb
a notebook to view data, make processing and transformation only for one file for simplicity.

### sql_queries.py
contains python scripts and SQL statement to create tables, insert data, select data and drop tables.

### test.ipynb
a notebook to displays the first few rows of each table to let you check your database, and some logic to confirm the creation of the tables with the correct columns.

## Database Schema

![Schema](https://firebasestorage.googleapis.com/v0/b/plantsexpertsystem-f6812.appspot.com/o/Untitled%20Workspace.png?alt=media&token=52f7a554-c5db-4f01-94d7-a46e38645fde)
this schema created using "creatly.com"


## Feedback

If you have any feedback, please reach out to us at mhuss073@uottawa.ca


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.credential.net/profile/mohamedaboalarbe/wallet)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-elaraby/)