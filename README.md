# Movie Industry Analysis

This project was completed as part of Flatiron School's Data Science Bootcamp (Module 1 Final Project).

## Business problem statement

Microsoft want to get in the movie industry, but they don’t know anything about creating movies. They have hired  a data science analyst to provide a data-driven understanding of the industry and characteristics of a successful movie.

## Objectives

1. Inform Microsoft about the state of the current movie industry

2. Use tool of data analysis to determine the characteristics of a successful movie

3. Make the informed recommendations about what makes a movie successful


## Project Overview

Based on the numbers of movie genres (during 2010 - 2022) and their individual average rating, I determined which genres are the most popular ones. Also, I defined the major competitors using the total gross income of each studio. Finally, I determined the directors whose movies have the highest average ratings based on viewers' number of votes (threshold 700,000). There are many more factors that determine a successful movie. The data analysis in this project paints a better picture of the movie industry overall and factors to consider in producing a successful movie.


## The Data

The analysis is based on the datasets which can be found in the data folder. It was provided by the Flatiron School.

I have decided to use following data files:

* imdb.title.basics
* imdb.title.ratings
* bom.movie_gross
* imdb.title.crew
* imdb.name.basics


## Methods

I imported data from the repository, then I cleaned data using different methods, for example, I dropped rows with missing values and filled null values when appropriate, converted datatypes, merged multiple dataframes, created columns. After data cleaning, I utilized descriptive statistics as well as visualizations to isolate three factors of a successful movies. I used matplotlib and seaborn to create 2 bar plots and one box plot to visualize data.Based on the data analysis which I conducted I could make informed recommendations.

## My Recommendations

1. One of the elements of a successful movie is its genre. According to both visualisations shown in the analysis, I would recommend that Microsoft considers those movie genres with less competition but still enough of public interest,for example, history and biography.

2. HC, P/DW, BV are the top three studios with over 400 million dollars average total gross income each. Because profit is another defining factor of a successful movie, I can consider those three studios competitors. Therefore, my second recommendation would be to analyse the work of the competitors to find out what is a competitive advantage Microsoft can have.

3. The third element that may contribute to making a successful movie is a professional director(s) whose movies draw viewers' attention and receive positive public reviews. Therefore, I would recommend that Microsoft hires(or analyse the movies of) directors that are within the top 10 most popular from the data analysis, even if the average movie rating is not the highest(10).

## For More Information 

Please revie my full analysis in my Jupyter Notebook or my presentation



