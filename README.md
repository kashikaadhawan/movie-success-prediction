# Movie Success Prediction

A machine learning mini project that predicts whether a movie will be a **Hit or Flop** based on pre-release information like budget, genre, popularity, and runtime.

## Definition
> **Hit** = Revenue ≥ 2 × Production Budget  
> **Flop** = Everything else

## Dataset
[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) from Kaggle.  
Download `tmdb_5000_movies.csv` and upload it when running the notebook.

## How to Run
1. Open `movie_success_prediction.ipynb` in [Google Colab](https://colab.research.google.com)
2. Run all cells from top to bottom
3. Upload `tmdb_5000_movies.csv` when Step 2 prompts you
4. To predict a new movie, edit the values in **Step 8** and run that cell

## Project Steps
| Step | Description |
|------|-------------|
| 1 | Import libraries |
| 2 | Load dataset |
| 3 | Clean data |
| 4 | Feature engineering |
| 5 | Exploratory Data Analysis (EDA) |
| 6 | Train models (Logistic Regression + Random Forest) |
| 7 | Evaluate models (Confusion Matrix, Classification Report) |
| 8 | Predict a new movie |

## Models Used
- Logistic Regression
- Random Forest *(better accuracy, used for final prediction)*

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
