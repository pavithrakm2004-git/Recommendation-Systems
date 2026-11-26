# Recommendation Systems

A Python notebook exploring recommendation-system concepts and comparing several recommendation approaches using the MovieLens 100K dataset.

## What the notebook covers

- Popularity-based recommendations
- User-based and item-based collaborative filtering
- Matrix factorisation with Alternating Least Squares (ALS)
- Genre-based content filtering
- A hybrid of matrix factorisation and content-based scores
- Exploratory data analysis, evaluation metrics, and sample recommendations

## Dataset

The notebook downloads [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/) from GroupLens when run. If the download fails, it uses synthetic data and prints a warning; those results are not from the MovieLens dataset.

## Setup and run

Requires Python 3.9 or later.

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter notebook Recommendation_System.ipynb
```

In Jupyter, run the cells from top to bottom to load the data, train the models, and view the evaluation and recommendations.

## Project files

- `Recommendation_System.ipynb` - explanations, implementation, results, and example recommendations
- `requirements.txt` - Python packages needed to run the notebook
