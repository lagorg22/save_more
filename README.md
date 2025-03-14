# Save More - ETL Pipeline for Product Pricing

## Overview

The **Save More** project is an ETL (Extract, Transform, Load) pipeline designed to collect, process, and analyze pricing data from multiple online retailers. The goal is to aggregate data from different stores, compare prices, and provide insights for consumers and businesses looking for the best deals. While the project currently focuses on tech products, it is planned to be expanded to include every possible kind of product available on the internet.

## Current Progress

- Successfully integrated **4 online stores** for data extraction.
- Implemented **web scraping** using `BeautifulSoup` and `Selenium` to gather product listings.
- Transformed raw data into structured format using `Pandas` and `NumPy`.
- Stored processed data in a **PostgreSQL** database.
- Designed a scalable database schema to handle multiple stores efficiently.

## Technologies Used

- **Web Scraping**: `BeautifulSoup`, `Selenium`
- **Data Processing**: `Pandas`, `NumPy`
- **Database**: `PostgreSQL`
- **Automation & Orchestration**: `Apache Airflow` (planned)
- **Containerization**: `Docker`
- **Backend API**: `Django Rest Framework` (planned)

## Roadmap

- **Expand Store Coverage**: Add more online stores for better price comparisons.
- **Automate ETL Workflow**: Implement `Airflow` to schedule and manage data collection.
- **Deploy with Docker**: Containerize the entire pipeline for easy deployment.
- **Expose API**: Build a RESTful API using `Django Rest Framework` to serve processed data.
- **Enhance Data Matching**: Improve product matching across stores using better hashing or machine learning.
- **Expand Product Categories**: Extend beyond tech products to include all product types available on the internet.



---

This project is a work in progress, and more features will be added soon. Stay tuned!


