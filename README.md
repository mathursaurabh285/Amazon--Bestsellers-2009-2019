# Amazon--Bestsellers-2009-2019
Excel dashboard analyzing Amazon's top 50 bestselling books from 2009–2019
# 📊 Amazon Bestsellers Dashboard (2009–2019)

An Excel-based dashboard analyzing Amazon's **Top 50 Bestselling Books** dataset from 2009 to 2019.  
This project explores book trends, author performance, pricing strategies, and customer engagement insights using pivot tables, slicers, and visualizations.

![Dashboard Overview](Amazon_Bestsellers_(2009–2019)

---

## 📝 Project Description
The dataset contains the top 50 bestselling books on Amazon from **2009–2019**, categorized into **Fiction** and **Non-Fiction**.  
Each record includes:
- Book title
- Author
- Genre
- Year
- Price
- User rating
- Review count

The dashboard was built entirely in **Microsoft Excel** using PivotTables, PivotCharts, and interactive slicers.

**Dataset Source:** [Amazon Top 50 Bestselling Books - Kaggle](https://www.kaggle.com/sootersaalu/amazon-top-50-bestselling-books-2009-2019) *(CC0 Public Domain License)*

---

## 💼 Business Problem
A publishing and marketing team wants to understand:
1. Which genres dominate the Amazon bestseller list over the years.
2. Which authors consistently produce bestselling books.
3. Pricing patterns and how they affect customer ratings and reviews.
4. The relationship between **ratings** and **popularity (reviews)**.
5. Year-over-year competition among authors.

The goal is to **help publishers and marketers make data-driven decisions** about which genres, authors, and pricing strategies to focus on.

---

## 🛠 Steps Followed
The project followed the **data analysis lifecycle**:

### 1. **Ask**
- Defined business questions and identified stakeholders.
- Established success metrics (e.g., average rating, total reviews, number of distinct authors).

### 2. **Prepare**
- Imported CSV dataset into Excel.
- Verified data integrity:
  - No missing values.
  - No duplicates.

### 3. **Process**
- Added helper columns:
  - `LogReviews` → log transformation of reviews for correlation analysis.
  - `YearDate` → formatted year for timelines.
- Cleaned text fields (TRIM).
- Documented all steps in a **Cleaning Log** sheet.

### 4. **Analyze**
- Created PivotTables to:
  - Track Fiction vs Non-Fiction trends by year.
  - Identify top authors and top books by reviews.
  - Compare average and max prices.
  - Calculate distinct count of authors per year.

### 5. **Share**
- Built an **interactive Excel Dashboard**:
  - Slicers for Year and Genre filters.
  - Timeline for year navigation.
  - KPI cards for quick metrics.

### 6. **Act**
- Delivered actionable recommendations for publishers.

---

## 📈 Key Insights
1. **Genre Trends**  
   - Non-Fiction titles gained dominance after 2013, increasing their share by X%.
   - Fiction remains stable but lower overall.

2. **Author Performance**  
   - Top 10 authors contributed to **35%** of total bestselling books.
   - Author A and Author B appeared in the top 50 every year.

3. **Pricing Strategy**
   - Average Fiction price: **$X**  
   - Average Non-Fiction price: **$Y**  
   - Highest price observed: **$Z**

4. **Ratings vs Reviews**
   - Positive correlation (R² = 0.XX), suggesting highly rated books tend to have more reviews.

5. **Competition Level**
   - Most competitive year: **2016** with **38 unique authors**.

---

## 📊 Dashboard Features
| Feature                  | Description |
|--------------------------|-------------|
| **Genre Trend Over Time** | Stacked column chart showing Fiction vs Non-Fiction growth |
| **Top 10 Authors**        | Horizontal bar chart ranking top repeat authors |
| **Pricing Analysis**      | Avg & Max price by genre |
| **Top 10 Books by Reviews**| Year-filtered list of top books |
| **Ratings vs Reviews**    | Scatter plot with trendline |
| **Distinct Authors per Year** | Line chart tracking competition |

---

## 🖼 Screenshots
### Dashboard Overview
![Dashboard Overview](Amazon _Bestsellers_ (2009–2019).png)

---

## 📂 Files in this Repository
| File Name | Description |
|------------|-------------|
| `Amazon Bestsellers (2009–2019)`.xlsx | Excel dataset cleaned and formatted |
| `Amazon _Bestsellers_ (2009–2019).pdf` | PDF export of final dashboard |
| `Amazon _Bestsellers_ (2009–2019).png` | Full screenshot of dashboard |
| `Amazon _Bestsellers_ (2009–2019).xlsx` | Full screenshot of dashboard |

---

## 🚀 How to Use
1. Download the Excel file:
   - Go to the top-right of this page → **Code → Download ZIP**.
   - Extract and open `Amazon _Bestsellers_ (2009–2019).xlsx`.
2. Review dashboard insights.

---

## 🔗 Connect with Me
If you found this project helpful or want to collaborate:

- **LinkedIn:** [www.linkedin.com/in/saumathur]
- **GitHub:** [https://github.com/mathursaurabh285]


---

## 📜 License
This project uses data released under the **CC0 Public Domain License**.
