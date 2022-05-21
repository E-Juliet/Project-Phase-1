# Exploratory analysis of best performing films at the box office
This project was completed as part of Moringa school Data Science phase 1

## Problem Statement
Exploring what type of films are currently doing the best at the box office in order to help Microsoft's new movie studio decide on what types of films to create

## Components
__Data__

Data was provide in form of zipfiles 


This project focused on three data sets

__1. title.basics.csv__

Which contains the following information for titles:

tconst (string): alphanumeric unique identifier of the title

primaryTitle (string): the more popular title / the title used by the filmmakers on promotional materials at the point of release

originalTitle (string): original title, in the original language

startYear (YYYY): represents the release year of a title. In the case of TV Series, it is the series start year

runtimeMinutes: primary runtime of the title, in minutes

genres (string array): includes up to three genres associated with the title

__2. title.ratings.csv__

 Which contains:

 tconst (string): alphanumeric unique identifier of the title

 averageRating: weighted average of all the individual user ratings

 numVotes: number of votes the title has received

__3. tn.movie_budgets.csv__

  Which contains:

  release_date: release date of the movie
  
  movie: title of the movie
  
  production_budget: production budget in US dollars
  
  domestic_gross:domestic gross in US dollars
  
  worldwide_gross: worldwide gross in US dollars

__Jupyter Notebook__

The Jupyter Notebook is our key deliverable and contains details of our approach and methodology, data mining and cleaning, visualisations, conclusions and recommendations.

__Non Technical Presantation__

An overview of the project's objectives,analysis,conclusion and recomendations

## Technologies used

* Python

* Pandas

* Matplotlib

* Seaborn

* Visual Studio Code


## Objectives

* To indentify which type of films have the highest votes

* To identify which type of films have the highest gross

* To find the average duration of a film

* To find the estimated cost(budget) of creating a film

## Key Findings

### Genres
* The type of films with the most number of votes were from a mixture of genres(action,adventure and science fiction) and not just one particular genre
![Genres](https://github.com/E-Juliet/Project-Phase-1/blob/main/Genres.png)

### Film release
* There was a significant rise in the number of films released from 2010 to 2017,but there was significant drop in 2019.This could be due to the covid_19 pandemic

![Release Year](https://github.com/E-Juliet/Project-Phase-1/blob/main/released%20films%20per%20year.png)

### Average rating
* Most films were averagely rated between 6 and 7 out of 10

![Rating](https://github.com/E-Juliet/Project-Phase-1/blob/main/averagerating.png)

### Budget
* The average budget of producing a film is around 36.5 million

### Runtime minutes
* The average runtime was 94 minutes

![Runtime](https://github.com/E-Juliet/Project-Phase-1/blob/main/runtime.png)

### Correlation 
#### Production budget vs gross
* There is a strong relationhip between the production budget and gross having a correlation coefficient of 0.732 with domestic gross aand 0.794 with worldwide gross

![Correlation](https://github.com/E-Juliet/Project-Phase-1/blob/main/production%20and%20gross.png)

## Recomendations
* The head of Microsoft's new movie studio should consider creating films with different genres and not just one partivular one.A combination of adventure,action and science fiction received more votes.

* The head of Microsoft's new movie should also ensure that they have enough capital because the average cost of producing a film is around 37 million US dollars.

* The head of Microsoft's new movie studio should consider creating film are not more than 2 hours

* There is also a significant return on investment due to the strong correlation between production budget and worldwide gross 







