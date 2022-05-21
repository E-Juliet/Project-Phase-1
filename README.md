# Exploritory analysis of best performing films at the box office
This project was completed as part of Moringa school Data Science phase 1

## Problem Statement
Exploring what type of films are currently doing the best at the box office in order to help Microsoft's new movie studio decide on what types of films to create

## Components
__Data__

Data was provide in form of zipfiles 


This project focused on three data sets

1. title.basics.csv 

Which contains the following information for titles:

tconst (string): alphanumeric unique identifier of the title
primaryTitle (string): the more popular title / the title used by the filmmakers on promotional materials at the point of release
originalTitle (string): original title, in the original language
startYear (YYYY): represents the release year of a title. In the case of TV Series, it is the series start year
runtimeMinutes: primary runtime of the title, in minutes
genres (string array): includes up to three genres associated with the title

2. title.ratings.csv

 Which contains:

 tconst (string): alphanumeric unique identifier of the title

 averageRating: weighted average of all the individual user ratings

 numVotes: number of votes the title has received

3. tn.movie_budgets.csv

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

The type of films with the most number of votes were from a mixture of genres(action,adventure and science fiction) and not just one particular genre






