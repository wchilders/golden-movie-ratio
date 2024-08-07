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

- **Data Exploration:** Jupyter notebooks or scripts to explore the dataset.

- **Analysis:** Using Python with the  Pandas package to clean the data.

- **Visualizations :** Using Matplotlib and Plotly to visualize my findings.

## Features

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files| Used 2 CSV files from kaggle          |
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged them with pandas. The calculated stats from various data points |
  | Make 3 matplotlib, and Plotly | Made various plots to show off my findings. |
  | Utilize a virtual environment      | Made a venv for this project to keep my computer clean. |
  | Notate your code with markdown cells in Jupyter Notebook | Included in my code, you will find clear notes describing each code block. |

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
