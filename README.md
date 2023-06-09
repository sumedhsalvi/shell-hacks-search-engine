﻿# shell-hacks-search-engine
 Submitted To: ShellHacks 2022
 ## Schonfeld Street ID Challenge
 ### Are you facing difficulties to find relevant information from huge data? Don't worry! We are here. We have built a performant search engine that will give you the most relevant data within 30 seconds.
 
 ## Inspiration
 We have seen most people struggle while searching for the required and relevant data from the huge dataset. That's a challenging task and we wanted to find a solution to this problem for a long time. Schonfeld Street ID Challenge asked for a similar problem, so we decided to dive deeper into this project for our hackathon.
 
 ## What it does
 we have given a dataset of securities and their street IDs. The challenge is to design a performant search engine that, given a query, will index all securities and their street IDs and return the most relevant securities ordered from most relevant to least relevant. We have built a search engine that will give results within 30 seconds or less for the huge dataset given by Schonfeld.

## How we built it
We started with the understanding of the problem statement. After that, we analyzed the dataset for potential challenges and did brainstorming the approach to tackle such problems. Then, we divided the tasks within our team - @Sanket started working on the backend API and @Sumedh started on the frontend UI. we have developed backend API using FastAPI (python) and used the FuzzyWuzzy library for string matching tasks. We designed a simple dashboard that will allow users to input queries and after clicking on the submit button it will populate the relevant data in tabular format. We developed UI using Angular that will fetch JSON data from backend API through service and display it on the dashboard. We have used GitHub for the project repo and deployed it on Heroku.

## Challenges we ran into
The most challenging part was handling a huge amount of data. We needed to find perfect as well as partial matches of the user query that could be the substring of the one string or the exact string within a security or street IDs. There could be a scenario where the query occurs multiple times in a single security record. So we extracted such matches, assigned their priority, and populated them based on ranking.

## Accomplishments that we're proud of
From our search engine, we achieved to give the result of a user query within 30 seconds or less and this could be a great accomplishment for us from this challenge.

## What we learned
We can tackle any kind of problem if we work together as a team and accomplish our goals.

## What's next for Schonfeld Street ID Challenge
We have enjoyed this challenge and we will try to better visualize the results and optimize our algorithm as a future scope.

## Built With
* Angular
* FastAPI
* GitHub
* Heroku
* Python

## Try it out
[shell-hacks-search-engine](https://search-engine-ui.herokuapp.com "Title")
