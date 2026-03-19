# Web Scraping & Data Engineering Pipeline Project

## Overview
This project demonstrates an end-to-end data pipeline that involves web scraping, data storage, database management, and automated data ingestion. The pipeline extracts data from an e-commerce website, processes it, and stores it across relational and NoSQL databases.

It highlights key data engineering concepts including data collection, transformation, storage, and pipeline automation.

---

## Tech Stack
- Python (BeautifulSoup)
- MySQL
- Apache NiFi
- MongoDB

---

## Project Workflow

### 1. Web Scraping
- Scraped data engineering book listings from an e-commerce website
- Extracted key attributes including title, author, publication year, rating, and price
- Structured the data into CSV format for further processing

### 2. Data Storage (Relational Database)
- Designed and implemented a MySQL database
- Created tables and imported CSV data into the database
- Ensured proper schema design for structured data storage

### 3. Data Analysis
- Developed SQL queries to retrieve and analyse stored data
- Extracted insights such as pricing trends and rating distributions

### 4. Data Pipeline (Apache NiFi)
- Built an automated dataflow using Apache NiFi
- Ingested data from multiple sources and routed it into a database
- Demonstrated workflow automation and data integration

### 5. MongoDB Integration
- Integrated MongoDB for flexible, NoSQL-based data storage
- Demonstrated handling of semi-structured data

---

## Key Features
- End-to-end data pipeline from data collection to storage and analysis
- Web scraping using Python and BeautifulSoup
- Relational database design and querying (MySQL)
- Automated data ingestion using Apache NiFi
- NoSQL database integration with MongoDB

---

## Key Learnings
- Web scraping and data extraction techniques
- Database design and SQL querying
- Data pipeline automation using Apache NiFi
- Differences between relational and NoSQL databases
- End-to-end data handling and processing workflows

---

## Dataset
- Scraped dataset of nearly 200 data engineering books from Packt Publishing (paperback & eBooks)
- Includes key attributes: book title, author(s), publication year, star rating, and price
- Structured into CSV and imported into relational and NoSQL databases for analysis and pipeline demonstration

---

## Project Background
This project was initially developed as part of a group assignment where tasks were divided across team members. To strengthen my understanding of the full data pipeline, I independently extended the project by exploring additional components including data ingestion, processing, and database integration.

---

## Future Improvements
- Increase dataset size and automate scraping process
- Enhance data cleaning and validation steps
- Expand analytics with more complex SQL queries
- Improve pipeline scalability and monitoring
