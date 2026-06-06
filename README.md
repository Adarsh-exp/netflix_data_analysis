# Netflix Data Analysis

Exploratory Data Analysis (EDA) project on Netflix movies and TV shows using Python. The notebook explores Netflix catalog trends, content distribution, ratings, genres, country-wise availability, and release patterns through clear data cleaning, feature engineering, and visual analysis.

## Project Overview

This project analyzes the Netflix titles dataset to answer questions such as:

- How many movies vs TV shows are available on Netflix?
- Which countries contribute the most Netflix content?
- How has Netflix content addition changed over time?
- What are the most common genres and ratings?
- Which months see the highest content additions?
- Are Netflix movies getting shorter over recent years?

## Dataset

The dataset used in this project is `netflix_titles.csv`, which contains Netflix catalog metadata including:

- Title type
- Director and cast
- Country
- Date added
- Release year
- Rating
- Duration
- Genre/category
- Description

Dataset size: 8,807 rows and 12 columns.

> Note: This project is intended for educational and portfolio purposes.

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```text
.
├── netflix_titles.csv
├── netflix_titles_eda.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Adarsh-exp/netflix_data_analysis.git
   cd netflix_data_analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook netflix_titles_eda.ipynb
   ```

4. Run all cells to reproduce the analysis and visualizations.

## Analysis Covered

- Data loading and initial inspection
- Missing value handling
- Feature extraction from `date_added`
- Movie vs TV show comparison
- Top countries by content count
- Content added per year
- Top Netflix genres
- Age-rating distribution
- Country-wise genre comparison
- Monthly content addition trend
- Movie duration trend analysis

## Key Insights

- Netflix has more movies than TV shows in the dataset.
- The United States contributes the highest number of titles.
- Content additions increased significantly in recent years.
- International content and drama-related categories are highly represented.
- The notebook includes visual analysis for ratings, genres, countries, and release trends.

## Future Improvements

- Add an interactive dashboard using Streamlit or Plotly.
- Include automated data quality checks.
- Compare Netflix content trends with other streaming platforms.
- Add exported charts for a visual project summary.

## Author

Adarsh Singh  
GitHub: [Adarsh-exp](https://github.com/Adarsh-exp)
