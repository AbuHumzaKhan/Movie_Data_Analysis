# 🎬 TMDB Movie Dataset Analysis

# 📌 Project Overview

This project analyzes the TMDB (The Movie Database) Movie Dataset v11, containing metadata about movies such as titles, genres, popularity, budget, revenue, and release details.
The goal of this project is to clean, explore, and visualize movie-related data to uncover insights about the film industry, trends, and performance indicators.

# 📂 Dataset Information

File Used: TMDB_movie_dataset_v11.csv

Key Features (Columns after cleaning):

id → Unique identifier for each movie

title → Movie name

genres → Genres associated with the movie

budget → Budget of the movie (in USD)

revenue → Revenue generated (in USD)

runtime → Duration of the movie (in minutes)

release_date → Release date of the movie

popularity → Popularity score

vote_average → Average rating

vote_count → Number of votes received

production_companies → Studios/companies involved

production_countries → Countries of production

spoken_languages → Languages spoken in the movie

⚠️ Note: Columns with only one unique value or irrelevant details were removed during preprocessing.

# 🛠️ Data Cleaning & Preprocessing

Steps performed:

Standardized column names → lowercase, underscores, removed special characters.

Removed duplicates → dropped duplicate movie records.

Dropped low-information columns → columns with only one unique value.

Handled missing values → treated NaN values in critical columns.

Filtered dataset → focused on relevant features for analysis.

# 📊 Exploratory Data Analysis (EDA)

The notebook performs detailed analysis using Pandas, Matplotlib, and Seaborn.

Key analysis performed:

🎥 Most popular genres over time

💰 Budget vs Revenue analysis

⭐ Movies with highest average ratings

📈 Trends in movie releases across years

🌍 Top production countries & companies

📌 Insights

Some potential insights derived (example placeholders — update with your findings):

Action and Drama are the most common genres.

Movies with moderate budgets ($50M–$100M) often achieve higher ROI compared to ultra-high-budget films.

There is a steady increase in the number of movie releases per year since the 1990s.

The USA dominates production, followed by India and the UK.

# ⚙️ Installation & Requirements

To run this notebook, install the required Python libraries:

pip install pandas numpy matplotlib seaborn

# 🚀 Usage

Clone this repository or download the notebook.

Place the dataset file TMDB_movie_dataset_v11.csv in the working directory.

Run the notebook:

jupyter notebook Untitled.ipynb

# 📌 Future Work

Apply Machine Learning models to predict movie revenue.

Perform Sentiment Analysis on user reviews.

Create an interactive dashboard in Power BI/Tableau.
