# Golden Movie Ratio
Data analytics project.

![](https://github.com/wchilders/golden-movie-ratio/blob/main/20thcf.gif)

## Overview
This is a project to use IMDd data from a Kaggle dataset to determine if there is any correlation between the runtime of a movie and it's rating on IMDb.
This will provide data to determine what the "ideal" runtime for a movie in a certain genre is.

## Data Files and Data Used
1. imdb_data: File contains the imdb-movies-dataset.csv which has the raw movie data for the project.
2. imdb_top1k: File contains the imdb_clean.csv which has the top 1,000 movies from IMDb.

### Project Structure
---

The project is organized as follows:

- **Data Exploration:** Jupyter notebooks to explore the dataset.

- **Analysis:** Using Python with the Pandas package to clean the data.

- **Visualizations :** Using Tableau to visualize my findings.

## Features

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files| Used 2 CSV files from kaggle.          |
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged them with pandas. The calculated stats from various data points. |
  | Make a Tableau dashboard to display your data | Made a Tableau dashboard. |
  | Utilize a virtual environment      | Made a venv for this project to keep my computer clean. |
  | Notate your code with markdown cells in Jupyter Notebook | Included in my code, you will find clear notes describing each code block. |

## Getting Started

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-project.git`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Open the Jupyter notebook gmr.ipynb
4. Follow instructions at top of notebook and view results at the bottom.

*Tip: If you would like to run the program multiple times to create multiple DataFrames for each genre, make sure to edit the name of the CSV file the filtered_df is being written to anywhere it appears (ex: run program once to filtered_data.csv, then change CSV name to filtered_data1.csv and run it again on a different genre.)

## Findings

Here is the link to my Tableau dashboard [Tableau](https://public.tableau.com/app/profile/walker.childers/viz/GoldenMovieRatio/GoldenRatioDashboard?publish=yes)

In my findings you'll see a dashboard with data for the Golden Movie Ratio in Dramas, Comedies, and Horror films.
1. For Dramas, the highest rated films had an avg runtime of 142 min and a rating of 9.3
2. For Horrors, the highest rated films had an avg runtime of 122 min and a rating of 8.1
3. For Comedies, the highest rated films had an avg runtime of 120 min and a rating of 9.5

###  Virtual Environment Instructions
---
1. After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.
1. Create a virtual environment in the project folder. 
1. Activate the virtual environment.
1. Install the required packages. 
1. When you are done working on your repo, deactivate the virtual environment.

Virtual Environment Commands

| Command | Linux/Mac | GitBash |
|---------|-----------|---------|
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |
