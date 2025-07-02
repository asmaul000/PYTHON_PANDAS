# PYTHON_PANDAS
# Netflix Data Analysis with Pandas & Kaggle API

This project explores and analyzes Netflix Movies and TV Shows using Pandas and IMDb metadata. The dataset is sourced directly from Kaggle using the Kaggle API and processed in Google Colab. The goal is to uncover content trends, genre popularity, and highly rated shows or movies available on Netflix.
## Dataset

- **Source**: [Kaggle - Full Netflix Dataset by OctopusTeam](https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset)
- Contains:
  - Title, Type (Movie/TV Show)
  - Genres
  - Release Year
  - IMDb Rating and Vote Count
  - Available Countries

## Features of the Notebook

✅ Uses **Pandas** and **NumPy** for data analysis  
✅ Handles **missing values**, **string parsing**, and **datetime operations**  
✅ Creates flags such as `high_rating` for IMDb rating ≥ 8  
✅ Visualizes content trends over time by genre  
✅ Uses the **Kaggle API** to download the dataset programmatically  
✅ Fully reproducible in **Google Colab**

## Analysis Goals

- Trend of Netflix content by year
- Most common genres and their popularity over time
- Top-rated content by IMDb rating and vote count
- Titles available in specific countries (e.g., Bangladesh)
- Data cleaning and preprocessing demonstrations

---

## How to Use

1. **Open the notebook in Google Colab**
2. **Upload your `kaggle.json` file** (Get it from [Kaggle > Account > Create New API Token](https://www.kaggle.com/account))
3. Run the setup cells to install the Kaggle API and download the dataset
4. Explore and modify the analysis as you wish!

---

## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `zipfile`
- `kaggle` (API)
