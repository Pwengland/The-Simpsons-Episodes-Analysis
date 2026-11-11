# The Simpsons Episodes Analysis
##  Overview
This project covers an analysis of the television series The Simpsons. It looks at IMDb ratings, U.S. television viewership, writers, directors, and release dates.

Using Python, I collected, cleaned and combined data from multiple sources to investigate trends over the show's run. The aim was to explore how the series has changed and identify patterns that have appeared over the course of its history.

## Key Questions
1. How has the U.S. television viewership of The Simpsons episodes changed over time?
2. How have the IMDb ratings of The Simpsons episodes changed over time?
3. Which writers have the highest IMDb ratings/viewerships?
4. Which directors have the highest IMDb ratings/viewerships?
5. Do highly-rated episodes also have high viewing figures and IMDb user engagement?

## Data Sources
The project uses data collected from the following sources:
- **Wikipedia**: episode information including titles, episode numbers, writers, directors, release dates, and U.S. viewing figures.
- **IMDb**: episode user ratings and number of votes.

## Data Cleaning and Preparation
The original datasets required several cleaning and preparation steps before an analysis could be performed.

These included:
- Combining episode tables from multiple seasons into a single Pandas DataFrame.
- Standardising column names and data types.
- Removing Wikipedia annotations and other unwanted text.
- Handling missing values and inconsistencies.
- Combining the IMDb user rating and number of votes data with the episode data.

## Exploratory Data Analysis
The analysis uses various tools to investigate trends and relationships in the data such as:
- U.S. viewership over time
- IMDb rating over time
- The most prolific and highly-rated writers
- The most prolific and highly-rated directors
- The relationship between IMDb ratings, number of votes, and U.S. viewership

## Key Findings
1. The viewership of The Simpsons has consistently declined over its run. There have been peaks in viewership within seasons, but the average viewership has largely decreased with later seasons.
2. The show's average IMDb rating initially increased for its first six seasons, before it began to steadily decline. After this, the IMDb rating mostly decreased, reaching its lowest point at season 30 whereafter a small uptick in rating occurred.
3. John Swartzwelder is the most prolific Simpsons writer, having written 58 episodes. The writer with the highest average IMDb rating is Greg Daniels, with an average rating of 8.7.
4. Steven Dean Moore is the most prolific Simpsons director, having directed 87 episodes in total. The highest-rated director on average was Rich Moore, with an average score of 8.3 for his episodes.
5. IMDb rating, U.S. viewership, and IMDb user engagement were found to be positively correlated with each other.

## Tools used
- Python
- Pandas
- Matplotlib
- Numpy
- Seaborn
- Jupyter Notebook
