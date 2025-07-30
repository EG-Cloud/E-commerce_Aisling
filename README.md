
# Book Sales Data Analysis Project

## Context & Objectives

The purpose of this project was to explore how **web scraping** could be integrated into a broader data workflow, including **data cleaning** and **Exploratory Data Analysis (EDA)** using **Python** and **PostgreSQL**. The main objectives were to clean a dataset containing various quality issues, import it into a PostgreSQL database via **pgAdmin4**, and conduct an EDA.

Bonus objectives included:
- Building a **web scraping script** to supplement the data
- Creating a **basic automation script** to streamline the workflow from CSV file to successful import into PostgreSQL

## Data Sources

The dataset was created using two primary sources:
- **Web scraping**, using BeautifulSoup to extract real book data
- **Fictional data generation** via ChatGPT to simulate user/customer behavior and fill in missing dimensions

## Tools & Methodology

This project used the following tools and libraries:
- **Python (VS Code)**: `pandas`, `matplotlib`, `seaborn`, `beautifulsoup4`
- **PostgreSQL (pgAdmin4)** for data storage, queries, and integration
- **Automation scripting** with Python to reduce manual CSV import steps

Key steps in the methodology:
1. Clean and preprocess the dataset in Python using Pandas
2. Load the cleaned data into PostgreSQL
3. Perform SQL queries and visual analysis using Python (Matplotlib/Seaborn)
4. Web scrape additional book data for enrichment
5. Create scripts to automate CSV-to-database import flow

## Key Results & Visualizations

### Buyer Persona & Customer Insights

- The **typical buyer** is a man or woman aged **56+**, from **Germany**, and is a **regular customer**.
- The **discount buyer** matches this persona: **German**, aged **56–65**, **regular**.
- **Age and revenue** are mildly related — older users tend to generate more revenue.

### Product Performance & Preferences

- **Top-selling books**:
  - *Scott Pilgrim's Precious Little Life*
  - *Tipping the Velvet*
  - *Soumission*
  - *A Light in the Attic*
  - *The Black Maria*

- **Top-rated books**:
  - *Set Me Free* – 3.61  
  - *Shakespeare's Sonnets* – 3.61  
  - *A Light in the Attic* – 3.51  
  - *The Coming Woman* – 3.46  
  - *Rip it Up and Start Again* – 3.44  

- **Most profitable category**: *Poetry*  
- **Least profitable category**: *Business*

- Preferences were similar between generations (pre/post-1990), especially for *Poetry*, *Young Adult*, and *Default* categories.

### Revenue & Seasonality

- **Summer months** are consistently the strongest in sales, indicating seasonal buying behavior.
- **Publishing houses** outperform individual sellers in both basket size and turnover.
- **Top revenue-generating sellers**:
  - Beth Keller
  - Kevin Cox
  - Melanie Herrera
  - Daniel Adams
  - Crystal Johnson

### Relationships & Correlations

- A weak negative correlation exists between **price and rating**, suggesting that higher-priced books may receive slightly lower ratings.

## Conclusion & Learnings

This project helped uncover meaningful insights into book buyer profiles, seasonal revenue trends, and product performance. From a technical perspective, it offered hands-on experience with:

- **BeautifulSoup**: Writing a basic but effective web scraping script
- **Pandas**: Data cleaning, transformation, and preparation for analysis
- **Matplotlib & Seaborn**: Creating clear, interpretable visualizations
- **PostgreSQL / pgAdmin4**: Designing and managing a relational database structure for analysis
- **Basic scripting**: Building a lightweight script to automate repetitive data loading tasks

These learnings strengthened my ability to manage data workflows from raw collection to business-ready insights — a valuable skill set for data analytics and data engineering projects.
