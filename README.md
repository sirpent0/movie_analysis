# Movies Analysis

An end-to-end data analysis project exploring movie trends, popularity, ratings, and genres using Python and Power BI.

---

## Project Structure

```
movies_analysis/
├── data/
│   ├── movies_raw.csv          # Original dataset
│   └── movies_analysis.csv     # Cleaned dataset
├── notebooks/
│   └── movies_analysis.ipynb   # Data cleaning & EDA notebook with visualizations as well
├── dashboard/
  └── MoviesAnalysis.pbix     # Power BI dashboard
```

---

## Dataset

**Raw Dataset columns:**

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Movie title |
| `Overview` | Short description of the movie |
| `Popularity` | Popularity score |
| `Vote_Count` | Number of votes received |
| `Vote_Average` | Average rating (out of 10) |
| `Original_Language` | Language the movie was produced in |
| `Genre` | Movie genre(s) |
| `Poster_Url` | URL to the movie poster image |

---

##  Data Cleaning

The raw dataset was cleaned using Python (pandas). The following steps were applied:

- **Dropped missing values** — rows with null entries were removed to ensure data quality
- **Dropped unnecessary columns** — `Overview` and `Poster_Url` were removed as they are not needed for analysis

**Cleaned Dataset columns:** `Release_Date`, `Title`, `Popularity`, `Vote_Count`, `Vote_Average`, `Original_Language`, `Genre`

---

## Analysis & Visualizations

The Power BI dashboard (`MoviesAnalysis.pbix`) includes insights such as:

- Most popular movies by popularity score
- Average ratings by genre
- Movie distribution by language
- Vote count trends over time


## Tools Used

- **Python** (pandas) — data cleaning
- **Jupyter Notebook** — exploratory data analysis
- **Power BI** — interactive dashboard and visualizations

---

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/movies-analysis.git
   cd movies-analysis
   ```

2. Install dependencies
   ```bash
   pip install pandas jupyter
   ```

3. Run the notebook
   ```bash
   jupyter notebook notebooks/movies_analysis.ipynb
   ```

4. Open `dashboard/MoviesAnalysis.pbix` in Power BI Desktop to explore the dashboard

---

## 📌 Dataset Source

Kaggle
