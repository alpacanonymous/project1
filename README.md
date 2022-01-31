# Recommendations for Microsoft Studios

**Authors:** Angela Kim, Aisha Baitemirova-Othman, Adonis McQueen, Deja Prade, James Kang
**Instructor:** David Elliott

## Overview

This project analyzes movie datasets from multiple databases to come up with a business plan for Microsoft's new movie studio.

## Business Problem & Key Questions

Microsoft wants to create a new movie studio but requires data-driven recommendations in order to decide what types of films to produce. We seek to answer the following questions:

* *Which films in the past decade have made the most profit?*
* *What are the genres of these films?*
* *Which films and genres are the most popular?*
* *Is there correlation between genre and profit?*
* *What is the relationship between genre and vote average?*
* *Can Microsoft capitalize on its own franchises?*
* *What can we learn from other production studios?*
* *Would it be cost-effective to acquire a smaller, already established studio?*

## Data Sources & Methods

Databases: IMDB, TheMovieDB, Box Office Mojo, the Numbers, and Rotten Tomatoes.

Methods: Exploratory Data Analysis (EDA)

## Data Understanding & Analysis

<img width="701" alt="Screen Shot 2021-10-29 at 11 07 19 AM" src="https://user-images.githubusercontent.com/92389914/139487597-d8f96448-fbe9-48f7-95d1-b25985a3f556.png">

This graph shows the correlation between the average ratings. Movies were given by genre, while genres can overlap, the focus of resources should be towards action, adventure, fantasy, sci-fi, comedy and crime movies. Crime has the highest rating, but the other 5 categories have higher volumes of consumer interaction.

<img width="995" alt="Screen Shot 2021-10-29 at 12 02 55 PM" src="https://user-images.githubusercontent.com/79756630/139467000-68f80c70-d829-4d7b-9a02-b12c30b22c23.png">

<img width="999" alt="Screen Shot 2021-10-29 at 11 52 23 AM" src="https://user-images.githubusercontent.com/79756630/139465728-1d25a967-4b93-4d1a-b5b9-4424c8992754.png">

According to the data from Rotten Tomatoes, the movie genres that get produced the most are drama, comedy, action, romance and animation or the combination of those. Out of those top genres, the drama and the comedy genres production have been mostly declining over the course of the last decade.    

<img width="1011" alt="Screen Shot 2021-10-29 at 2 55 23 PM" src="https://user-images.githubusercontent.com/79756630/139489548-a5a55342-2022-4b80-9f05-c532e9bdffd2.png">

The average critical rating was the highest for the "Art House and International", the drama and the comedy genres compared to others. 

<img width="990" alt="Screen Shot 2021-10-29 at 11 47 16" src="https://user-images.githubusercontent.com/92397144/139473984-c5cf8337-2353-4963-93a8-5f53bef0f07f.png">

Over the last decade, domestic and worldwide film profits reveal general audiences gear toward familiarity, vastly preferring sequels and already established franchises over original content. They also show that the majority of the most profitable films of the last decade have been produced by Buena Vista and Universal Pictures.

<img width="1046" alt="Screen Shot 2021-10-29 at 10 24 53 AM" src="https://user-images.githubusercontent.com/79756630/139489715-1cae4f6d-1c66-4155-9adc-2f6f25c56244.png">

67% of the top 30 films that made the highest domestic profits were produced by either Buena Vista or Universal Pictures, and when we take a look at worldwide profits, that market share is even higher at 73%.

<img width="1020" alt="Screen Shot 2021-10-28 at 9 24 37 PM" src="https://user-images.githubusercontent.com/79756630/139466192-a2e64ef6-c281-4bbd-8c6e-9c791cb0290d.png">

<img width="997" alt="Screen Shot 2021-10-28 at 9 28 16 PM" src="https://user-images.githubusercontent.com/79756630/139405185-33396ed5-1e8c-459b-9d62-d247f37466a8.png">

Franchise films and the studios that produce them have the highest domestic gross. The second visual shows us that smaller studios (IFC, SPC, Wein), while creating a lot of content, do not yield the same gross. Therefore, we recommend that Microsoft focuses on content based on their own gaming properties to create content. 

<img width="1013" alt="Screen Shot 2021-10-29 at 12 53 51 PM" src="https://user-images.githubusercontent.com/79756630/139489812-cb58c0b6-0c24-4982-b1ee-e15d450142be.png">

Studio acquisition is highly recommended, as the top content producers all operate under parent companies. Mini-major studios such as Relativity Media can be
acquired by Microsoft to boost content production.

<img width="1005" alt="Screen Shot 2021-10-29 at 12 44 28 PM" src="https://user-images.githubusercontent.com/79756630/139489846-fc7cfb15-ac9f-4c61-b36e-81837ef3597e.png">

## Conclusions
This analysis leads to three recommendations for Microsoft's new movie studio.
* The consistent trend of movies in the last decade have geared towards drama, action, and comedy, or a combination of the three. Therefore, we recommend Microsoft focus on making movies like this because of the correlation between these three genres and profits.
* Any action/scifi/adventures movies made should be based upon Microsoft properties (Halo, Minecraft, etc). The highest grossing films are all established properties with large fanbases, and it is our recommendation that Microsoft follow suit with their own. This will ensure Microsoft isn't burdened with license and copyright fees for action content production.
* Microsoft should strongly consider acquiring an additional studio for content production. The most successful studios are all under a parent company, and Microsoft would greatly benefit by following their example.


```
├── [data]
│    ├── bom.movie_gross.csv.gz
│    ├── imdb.name.basics.csv.gz
│    ├── imdb.title.akas.csv.gz
│    ├── imdb.title.basics.csv.gz
│    ├── imdb.title.crew.csv.gz
│    ├── imdb.title.principals.csv.gz
│    ├── imdb.title.ratings.csv.gz
│    ├── rt.movie_info.tsv.gz
│    ├── rt.reviews.tsv.gz
│    ├── tmdb.movies.csv.gz
│    └── tn.movie_budgets.csv.gz
├── [images]
├── [pdfs]
│    ├── github.pdf
│    ├── notebook.pdf
│    └── presentation.pdf
├── .gitignore
├── README.md
├── notebook.ipynb
└── presentation.pdf
```
