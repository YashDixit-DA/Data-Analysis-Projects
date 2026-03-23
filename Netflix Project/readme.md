
# Netflix Content Analysis Dashboard

## Project Overview

This project presents an end-to-end **data analysis and visualization pipeline** for Netflix content using:

* Power BI Dashboard
* Python (Jupyter Notebook)
* Cleaned Dataset (CSV)

The goal is to uncover insights about **content quality, popularity, audience trust, and long-term value** of shows on Netflix.

---

## Project Structure

```bash
├── CLeaned_CSV.csv        # Cleaned dataset used for analysis
├── Netflix_project.ipynb  # Data cleaning & preprocessing (Python)
├── Final Report Backup.pdf # Power BI dashboard & insights
├── README.md              # Project documentation
```

---

## Tools & Technologies

* Python (Pandas, NumPy)
* Jupyter Notebook
* Power BI
* Data Visualization Techniques

---

## Key Insights

### 1. Executive Overview

* Total Shows: 10K
* Average Rating: 6.83
* Blockbuster Content: 5.42%
* Average Popularity: 7.83

The platform is heavily dominated by low-impact and average-performing content, with only a small fraction of blockbusters.

---

### 2. Content Quality & Audience Trust

* High vote content has an average rating of 7.7
* Low vote content drops to 4.9
* Weighted ratings better reflect true audience trust

Insight:
Popularity alone is misleading — trust is better captured through weighted ratings.

---

### 3. Popularity vs Long-Term Value

* Blockbusters dominate popularity (34.4 avg popularity)
* Hidden gems have high ratings but low visibility
* Overhyped content shows high popularity but low ratings

Insight:
High popularity does not necessarily indicate high quality.

---

### 4. Genre Analysis

* Total genres analyzed: 19
* Genres like Drama, Crime, and Mystery perform best in:

  * Ratings
  * Popularity
  * Weighted scores

Insight:
Certain genres consistently deliver higher long-term value.

---

### 5. Cohort & Trend Analysis

* Most content produced: 2010–2019
* Best performing cohort: 2010–2019 (highest weighted rating ~6.99)
* Sustainable content: 15.83%

Key takeaway (from report):

> “Popularity fades. Weighted ratings reveal trust. Sustainable platforms invest in trust.” 

---

## Dashboard Screenshots

### Content Quality & Audience Trust

(Page 2 of report)
![Content Quality](images/content_quality.png)

---

### Popularity vs Long-Term Value

(Page 3 of report)
![Popularity vs Value](images/popularity_value.png)

---

### Genre Analysis

(Page 4 of report)
![Genre Analysis](images/genre_analysis.png)

---

### Cohort & Future Investment Insights

(Page 5 of report)
![Cohort Analysis](images/cohort_analysis.png)

---

## How to Use

1. Run the Jupyter Notebook:

   ```bash
   Netflix_project.ipynb
   ```
2. Load the cleaned dataset (`CLeaned_CSV.csv`)
3. Open the Power BI report (if available) or use the PDF for insights
4. Explore dashboards and apply filters

---

## Key Learnings

* Data cleaning is critical before visualization
* Weighted metrics are more reliable than raw metrics
* Visualization helps uncover hidden patterns
* Not all popular content delivers long-term value
