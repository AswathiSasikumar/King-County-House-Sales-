# Microsoft Movie Analysis
![director_shot](https://user-images.githubusercontent.com/103409242/164956421-8782bdf2-c8f6-46a9-93c2-f4686f84335e.jpeg)

**Authors**:<font color='Blue'> Aswathi Sasikumar </font>

## Overview

This project analyzes the types of movies that are currently doing the best at the box office.This will give insights to Microsoft about the current trends in Movie Market and will enable them to devise strategies for their new Movie Studio.

## Business Problem

Microsoft will be able to understand the latest trends in the movies market.They will be able to make following inferences from the analysis.

* Identify the genres that are getting the highest votes/rating from public.
* Identify the genres that are marking profit in domestic and international market
* Identify the studios that are making trend setter movies.

They can utilize these findings in deciding upon the movies they should create in their new Movie Studio to get maximum profit.

The datasets from the popular movie datasets were used for this analysis mainly:

* IMDB
* BOX Office MOJO

## Data

IMDb is the world's most popular and authoritative source for movie, TV and celebrity content.One can find in it the ratings and reviews for the newest movie and TV shows.IMDB dataset contains rating and number of votes given to each movie.

1. imdb.titles.basics data set
IMDB Basics data set contains movie records of the period 2010-2115.Each movie is identified by an index "tconst".The other columns are year,runtime minutes,genres

2. imdb.titles.ratings data set
IMDB Ratings data set contains the average ratings and number of votes of each movie title.In this table too a movie/title is identified by the column "tconst".

Box Office Mojo is an American website that tracks box-office revenue in a systematic, algorithmic way.

1. Bom.movie_gross dataset
This dataset has details of the domestic gross and foreign gross earned from each movie and the name of studio which produced the movie along with year in which it was produced.

## Methods

Descriptive Analysis approach was used to analyse the data and to draw conclusions.The three datasets were merged and conclusions were drawn on the following:

* Genres that are getting the highest votes/rating from public.
* Genres that are marking profit in domestic and international market
* Identify the studios that are making trend setter movies.This analysis leads to three recommendations for the new Microsoft Movie Studio.


## Results

The Findings of the analysis are detailed below:
1.Short,Documentary,Game-Show are the genres which got high ratings.

![Genre_Rating](https://user-images.githubusercontent.com/103409242/164956460-78c23bd0-be85-4970-9159-4b11b03423be.png)

2.Sci-Fi,Adventure,Animation got the maximum gross revenue.

![Genre_Revenue](https://user-images.githubusercontent.com/103409242/164956463-db74b94c-2bd8-434e-8ce2-81947114cb84.png)

3.Analysis of the trends in top voted movies in the IMDB data Set showed that the top voted movies belonged to genres Action,Adventure,Sci-FI.

![Top](https://user-images.githubusercontent.com/103409242/164956465-870cd2da-ba7f-4317-aded-7f46e46c3b3b.png)

4.Analysis of Domestic gross earned by top studios over the years showed that BV studio is earning highest domestic gross consistenly.

![TopStudio_Dom](https://user-images.githubusercontent.com/103409242/164956484-9ed5608f-92ba-4da0-962b-c4e7f6f14439.png)

5.From this plot we can see that even though BV studio has got the highest foreign gross in box office,there has been a dip in its revenue earned in 2018.And the performance of WB studio has been increasing.

![TopStudio_Foreign](https://user-images.githubusercontent.com/103409242/164956487-44069d40-8876-4ba9-8c93-7bcf0a73a5c6.png)

## Conclusions

* Inorder to get maximum revenue genres like Sci-Fi,Adventure,Animation is to be considered.
* For getting good rating genres like Short,Documentary,Game-Show is preferrable.
* Highest number of votes was obtained for genres like Adventure,Sci-Fi,Action.
* For collaboration BV studio can be considered which has performed consistently on the basis of domestic gross earned.WB studio can also be cosnidered as its performance has been improving lately on the basis of foreign gross earned.

## Limitations

** Based on the analysis we were able to understand the current trends at the box office.However the success of a movie depends on multiple factors such as the crew,a bold script, screenplay and the marketing strategies adopted.
Eg: The movie ‘Justice League’ released in 2017 bombed at the box office despite it’s starstudded cast and action sequences ,the movie was criticized for its underdeveloped plot and resulted in studio loosing its money.

** Also while analysing the top movies based on number of votes it was found that though every year the top voted movie belonged to the genre Action,Adventure,Sci-Fi.In 2013,the top voted movie was “The Wolf of Wall street” which 
belonged to genre “Biography,crime” which clearly shows that bold script can definitely make a difference.


## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact ** Aswathi Sasikumar at [kukkuaswathi@gmail.com](mailto:alison.kukkuaswathi@gmail.com)

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
