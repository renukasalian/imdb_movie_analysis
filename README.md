# imdb_movie_analysis
This project explores and analyzes IMDB movie data stored in a SQLite database. Using Python (pandas, numpy,sqlite3), the project answers key questions about movies, directors, budgets, revenues, and popularity.


The Jupyter Notebook (imdb_movie_analysis.ipynb) connects to an SQLite database (movie.sqlite) and performs:

Data Loading & Exploration
-Extracts tables: movies, directors.
-Creates pandas DataFrames for easy manipulation.
-Explores dataset structure with .info() and schema inspection.

Movies Analysis
-Count of total movies in database.
-Most popular movies by popularity score.
-Highest budget movies (Top 10).
-Highest revenue movies (Top 10).
-Movies with highest vote averages.
-Comparison of vote_average vs vote_count.

Directors Analysis
-Queries for specific directors (James Cameron, Luc Besson, John Woo, Steven*).
-Count of female directors & identifying the 10th female director.
-Movies directed by Brenda Chapman.
-Director with most movies.
-Most bankable director (highest cumulative budget).
-Director-wise movies and revenue analysis.

Budget & Revenue Analysis
-Top 10 highest budget movies.
-Top 10 revenue generating movies.
-Breakdowns of budget vs revenue performance.
