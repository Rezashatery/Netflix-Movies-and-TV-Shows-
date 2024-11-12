# Netflix Titles Analysis

This project analyzes a dataset of Netflix titles, including movies and TV shows. It performs data cleaning, exploratory data analysis, and visualization to gain insights into the Netflix catalog.

## Dataset

The dataset used in this project is `netflix_titles.csv`. It contains information about Netflix titles, such as show ID, type, title, director, cast, country, release year, rating, duration, listed in, and date added.

## Code Overview

The code is written in Python and utilizes libraries like Pandas, NumPy, Matplotlib, and Seaborn. It performs the following steps:

1. **Importing Libraries:** Imports necessary libraries for data analysis and visualization.
2. **Reading Data:** Reads the `netflix_titles.csv` file into a Pandas DataFrame.
3. **Data Cleaning and Exploratory Analysis:**
   - Checks for and handles duplicated values.
   - Checks for and handles missing values.
   - Converts data types for relevant columns (e.g., `date_added` to datetime).
   - Extracts loading year and month from the `date_added` column.
   - Splits the `duration` column into minutes and units.
4. **Visualization:**
   - Creates visualizations to explore the distribution of loading years, release years, content types, and more.
   - Generates bar plots, pie charts, and heatmaps to represent the data.
5. **Specific Analysis:**
   - Answers specific questions about the dataset, such as the number of movies and TV shows, titles released in specific years or countries, top directors, and content with specific ratings.

## Insights

The analysis provides insights into the Netflix catalog, such as:

- The distribution of content types (movies vs. TV shows).
- The trend of content loading and release years.
- The most prolific directors.
- The prevalence of different ratings.
- The distribution of content across countries.

## Usage

To run the code, you will need to have Python installed along with the required libraries. You can install them using `pip`:
