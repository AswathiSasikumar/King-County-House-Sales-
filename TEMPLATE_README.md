# Microsoft Movie Analysis

**Authors**: Aswathi Sasikumar

## Overview

This project analyzes the types of movies that are currently doing the best at the box office.This will help Microsoft in understanding that the current trends in Movie Market and will enable them to decide upon the movies for their New Movie Studio.

## Business Problem

Microsoft will be able to understand the latest trends in the movies that are making big profit in Box-office.They will be able to make following inferences from the analysis.

* Identify the genres that are getting the highest votes/rating from public.
* Identify the genres that are marking profit in domestic and international market
* Identify the studios that are making trend setter movies.

They can utilize these findings in deciding upon the movies they should create in their new Movie Studio to get maximum profit.

The datasets from the popular movie datasets were analysed.

IMDB
BOX Office MOJO


## Data

IMDb is the world's most popular and authoritative source for movie, TV and celebrity content.One can find in it the ratings and reviews for the newest movie and TV shows.IMDB dataset contains rating and number of votes given to each movie.Box Office Mojo is an Americanwebsite that tracks box-office revenue in a systematic, algorithmic way.

1. IMDB Basics data set
IMDB Basics data set contains movie records of the period 2010-2115.Each movie is identified by an index "tconst".The other columns are year,runtime minutes,genres

2. IMDB Ratings data set
IMDB Ratings data set contains the average ratings and number of votes of each movie title.In this table too a movie/title is identified by the column "tconst".

3. Bom.movie_gross dataset
This dataset has details of the domestic gross and foreign gross earned from each movie and the name of studio which produced the movie.

## Methods

Descriptive Analysis approach was used to analyse the data and to draw conclusions.The three datasets were merged and conclusions were drawn on the following:

* Genres that are getting the highest votes/rating from public.
* Genres that are marking profit in domestic and international market
* Identify the studios that are making trend setter movies.This analysis leads to three recommendations for the new Microsoft Movie Studio.


## Results

This analysis leads to three recommendations for the new Microsoft Movie Studio.

Inorder to get maximum revenue genres like Sci-Fi,Adventure,Animation is to be considered.
For getting good rating genres like Short,Documentary,Game-Show is preferrable.
Highest number of votes was obtained for genres like Adventure,Sci-Fi,Action.
For collaboration BV studio can be considered which has performed consistently on the basis of domestic gross earned.WB studio can also be cosnidered as its performance has been increasing lately on the basis of foreign gross earned.


## Conclusions

Limitations
Even though we understood the latest trends in terms of genres,the success of the movie studio depends on the selection of crew members and getting a story based on the genre recommendation that can produce box office hits.

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
