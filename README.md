#  Bestseller Books Analysis (2009–2019)

This project analyzes **Amazon's Top 50 Bestseller Books dataset (2009–2019)** using Python.  
The script explores bestselling books by **genre, year, author trends, and review statistics** with data cleaning, preprocessing, and visualization.

---

##  Features

- **Data Cleaning & Preparation**
  - Standardized author names (e.g., *"J. K. Rowling"* → *"J.K. Rowling"*).
  - Added derived features:
    - `name_len`: length of book titles excluding spaces.
    - `punc%`: percentage of punctuations in book titles.

- **Exploratory Data Analysis (EDA)**
  - Distribution of **Fiction vs Non-Fiction** across years.
  - Top bestselling authors by **frequency & genre**.
  - Unique books vs duplicate appearances.
  - Total reviews for top authors.

- **Data Visualization**
  - Pie charts showing genre distributions.
  - Year-wise breakdown of book genres (2009–2019).
  - Bar charts for bestselling authors (Fiction & Non-Fiction).
  - Comparative analysis of appearances, unique books, and total reviews.

---

## Dataset

The dataset used: **`bestsellers with categories.csv`**

It contains the following columns:
- **Name** → Book title  
- **Author** → Book author  
- **User Rating** → Average user rating  
- **Reviews** → Number of reviews  
- **Price** → Price of the book  
- **Year** → Year it was a bestseller  
- **Genre** → Fiction / Non-Fiction  

---

## Installation & Requirements

Clone the repo:

```bash
git clone https://github.com/your-username/bestseller-books-analysis.git
cd bestseller-books-analysis
