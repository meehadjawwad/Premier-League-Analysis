# Premier League Analysis

## Aim of the Project

The aim of the project was to:

- Combine the results of the last five premier league seasons.
- Analyse clubs' performances in regards to:
	- Attack metrics
	- Defence metrics
	- Overall results
- Generate an accumulated points table.
- Identify clusters of clubs based on overall performance.

## Table of Contents

1. [Hardware Used](https://github.com/meehadjawwad/Premier-League-Analysis#hardware-used)
2. [File Descriptions](https://github.com/meehadjawwad/Premier-League-Analysis#file-descriptions)
3. [Methods Used](https://github.com/meehadjawwad/Premier-League-Analysis#methods-used)
4. [Technologies Used](https://github.com/meehadjawwad/Premier-League-Analysis#technologies-used)
5. [Executive Summary](https://github.com/meehadjawwad/Premier-League-Analysis#executive-summary)
	* [The Data](https://github.com/meehadjawwad/Premier-League-Analysis#the-data)
	* [Data Cleaning](https://github.com/meehadjawwad/Premier-League-Analysis#data-cleaning)
	* [Feature Engineering](https://github.com/meehadjawwad/Premier-League-Analysis#feature-engineering)
	* [Data Analysis](https://github.com/meehadjawwad/Premier-League-Analysis#data-analysis)
	
## Hardware Used

```
MacBook Pro (Retina, 13-inch, Early 2015)
Processor: 2.9 GHz Dual-Core Intel Core i5
Memory: 8 GB 1867 MHz DDR3
OS: macOS Catalina (version 10.15.3)
```

## File Descriptions

* images: folder with images
* data:
	* [`15-16.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/15-16.csv): raw data file for the 2015-16 season.
	* [`16-17.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/16-17.csv): raw data file for the 2016-17 season.
	* [`17-18.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/17-18.csv): raw data file for the 2017-18 season.
	* [`18-19.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/18-19.csv): raw data file for the 2018-19 season.
	* [`19-20.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/19-20.csv): raw data file for the 2019-20 season.
	* [`clean_data.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/clean_data.csv): all raw data compiled and cleaned
	* [`feature_eng_data.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/feature_eng_data.csv): preliminary feature engineering on cleaned data
	* [`table.csv`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/data/table.csv): accumulated points table generated as a .csv file
* jupyter_notebooks:
	* [`analysis.ipynb`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/jupyter_notebooks/analysis.ipynb)
	* [`cleaning.ipynb`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/jupyter_notebooks/cleaning.ipynb)
	* [`feature_engineering.ipynb`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/jupyter_notebooks/feature_engineering.ipynb)
* [`analysis.md`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md): markdown file for detailed analysis
* [`dashboards.md`](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/dashboards.md): markdown file for dashboards

## Methods Used

* Data Cleaning
* Feature Engineering
* Data Analysis
* Data Visualisation

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Tableau

## Executive Summary

### The Data

The data, acquired from [Kaggle](https://www.kaggle.com/mrmorj/premier-league-football-data), is a collection of [Premier League](https://www.premierleague.com/home) results for the seasons: 2015-16, 2016-17, 2017-18, 2018-19, and 28 matches (up till 9 March) in the 2019-20 season.

### Data Cleaning

In the data cleaning phase, I changed the column names for all raw data files, and combined them into a single dataframe. I also checked for missing data, and ensured that the new dataframe was not missing any data from the smaller files.

### Feature Engineering

Featuring engineering on the data was conducted in two parts.

In the first part, I took the `cleaning.ipynb ` and generated new columns from `ht_score` and `ft_score`. They included:

* `firsthalf_home_goals` and `firsthalf_away_goals`: number of goals for both the teams in the first half.
* `secondhalf_home_goals` and `secondhalf_away_goals`: number of goals for both the teams in the second half.
* `total_home_goals` and `total_away_goals`: total number of goals for both the teams.
* `firsthalf_result`: the team that wins the first half.
* `secondhalf_result`:the team that wins the second half.
* `result`: the team that wins the match.

The second part of feature engineering was conducted alongside and according to the analysis.

### Data Analysis

For most analyses, I calculated the average number of games that the clubs have played, and filtered away all clubs that had played less than that number. The reason for this was to eliminate bias arising from smaller numbers.

_For example:_

_Club A has played 100 games and scored 49 goals. Club B has played 2 games and scored 1 goal. In this situation, the 'Goals Scored per Game' for Club A is 0.49, and Club B is 0.50. On paper, Club B has a better ratio, but in reality, the comparison is unfair._

The average number of games played was 124.69, which eliminated 14 out of 29 clubs.

### Dashboards

Two dashboard concepts are presented [here](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/dashboards.md), including notes on design thinking and future ideas.

