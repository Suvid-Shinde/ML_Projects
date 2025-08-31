#  Bestseller Books Analysis (2009–2019)

This project analyzes Amazon's Top 50 Bestseller Books dataset from 2009–2019 using Python. It explores genre trends, bestselling authors, and review patterns through data cleaning, feature engineering, and visualizations.

---

##  Features

- **Data Cleaning & Processing**
  - Standardizes author names (e.g., "J. K. Rowling" → "J.K. Rowling")
  - Adds derived features:
    - `name_len`: title length excluding spaces
    - `punc%`: punctuation percentage in titles

- **Exploratory Data Analysis**
  - Trends in Fiction vs Non-Fiction over time
  - Top authors by appearance frequency and genre
  - Unique vs duplicate book entries
  - Total reviews per author

- **Visualizations**
  - Pie charts by genre
  - Year-wise genre breakdowns
  - Bar charts for top authors
  - Comparative plots of appearances, unique titles, and review counts

---

##  Dataset

- **`bestsellers with categories.csv`** — Contains:
  - Name (book title)
  - Author
  - User Rating
  - Reviews
  - Price
  - Year
  - Genre (Fiction / Non-Fiction)

---

##  Installation & Requirements

1. Clone this repository:
    ```bash
    git clone https://github.com/Suvid-Shinde/ML_Projects.git
    cd ML_Projects
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
   *(or manually install: pandas, numpy, matplotlib, seaborn)*

---

##  Usage

Run the analysis script:

```bash
python code.py
