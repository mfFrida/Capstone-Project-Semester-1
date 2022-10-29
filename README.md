## Introduction

Computing Vision has decided to create a new movie studio, but they need to gain more background in making movies. They have hired us to help them better understand the movie industry. As consultants, we were in charge of data analysis and creating a presentation that explored what types of films are currently doing the best in the industry, translating those findings into actionable insights.

Our first approach was to identify what success looks like for a Film and what those success metrics were. To accomplish this, we have to prepare, model, visualize and interpret the data that allowed us to analyze the movies that have been produced since 2010—using public movie databases like IMDB, Box Office Mojo, Rotten Tomatoes, the Number, and the MovieDB. 

While analyzing the data, we establish what characteristics of films make them do best at the box office. Where among the multiple variables that we found, the most relevant that had a direct impact on the grossing and profit were:
- Popularity
- Ratings
- Genre
-Runtime

The movies databases were analyzed by utilizing Python with the following software libraries:

- Pandas: for handling all the data manipulation and analysis and allowing us to give structure and operations for manipulating all the numerical tables and time series.

-Numpy: it contains many functions for numerical computation, multidimensional arrays and matrix data structures (vectors, matrices, polynomials, etc.)

-Matplotlib: it allows us to trace and visualize data in the form of graphs.

-Seaborn: it complements Matplotlib by providing attractive statistical graphics.

Lastly, we create an Action Drama film that focuses on a war between cops and superheroes that follows a young, former officer whose family was killed by superheroes and teams up with cops to protect the big city. 

## As an overview, our Key findings were:

- For the last ten years, adventure, Comedy & Drama ​have been the Most Popular Genre​.
- Runtimes of 2 Hours or Longer Have a Positive Impact on Both Ratings and Domestic/Worldwide Revenue​.
- Higher Ratings Generate Higher Returns​

## Which are the most popular genres from the last decades?​

We could only start by looking at what genres are the most popular. There are many genres, each averaging a wide profit distribution since 2010. Looking at the top 12 genres over time, we can paint a picture of the total number of movies each genre produced over the years (1900–present). Most of the time, action has made the most profit over the years. With a pie chart, we visualize which genres have recently been increasing or decreasing in popularity. From 2016–2018, Action and Comedy films have been producing a steep increase in Total Profit. Furthermore, we created a vocabulary based on the film's synopsis for each genre per decade, using NLP we determined that the most repeated words were:​

Action and Adventure​
'time', 'stars', 'police', 'superman', 'three'​, 'wife', 'family', 'cop', 'time', 'war', 'way', 'star', 'young', 'city', 'thriller'​, 'together', 'help', 'former', 'team' 

Comedy​
'town', 'begins', 'young', 'friend', ​'school', 'makes', ​'family', 'love', 'begins', 'day', 'soon'

Drama​
'years', 'husband', 'woman', 'mother'​, 'family',  'time', 'young', 'begins', 'team', 'coach', ​'star', 'love', 'true', 'based'

To find the most famous content in the film industry, we joined the synopsis per genre and cleaned the vocabulary. Finally, we count the repetitions of each word and sort them to obtain the most popular "keywords" to create our recommendations.

Based on the available data, the film genres Adventure, Comedy, War, Action, and Fantasy could produce great results. The leading profit genres, Action, Rom-Com, and Adventure, paint a more reliable story.

## Does the Runtime have a direct impact on Revenue?

To determine the perfect or most accepted RuntiSme for the movie, we performed a statistical analysis to determine if there was a statistically significant positive or negative relationship between Runtime and Revenue. We tested five samples of runtime ranges, which were determined by observing how the Academy of Motion Picture Arts and Sciences and the Screen Actors Guild define movie types by their Runtime. We identified that from these different samples, the most relevant to the business case are movies with 120 minutes or longer runtimes. 

From all the steps mentioned above, we obtain statistically significant positive results for domestic and worldwide gross Revenue​. ​With the help of a bar graph, we analyze that the means illustrate a positive relationship. So the average rating of a movie has a significant connection to each of these time ranges​: 

- Less than 40 Minutes = significant +​
- 40 to 60 minutes = significant +​
- 60 to 90 minutes = significant -​
- 90 to 120 minutes = significant +​
- 120 and more minutes = significant +​

These runtimes were chosen according to the Academy of Motion Picture Arts and Sciences standards and the Screen Actors Guild.​

## Explore Opportunity:
​
- Explore how to properly allocate funds to different roles and aspects of creating a film ​
- Dive deeper into marketing costs and explore marketing channels ​
- Analyze generational trends to properly determine the most popular genres and create predictive models to decide what will be "hot." ​
- Create an optimization model to determine the best amount of money to use for the production budget to maximize profits 

## Recommendations

1. Create a Comedy, Action, or Drama film. ​

2. The film's length should be 120 minutes or longer to capture positive relationships between Runtime and rating as well as runtime and revenue outlook.​

3. Focus on creating quality films, then, when brand recognition is established, focus on marketing to prevent external costs from impacting the bottom line

## What would be the next steps?

1. Plan: Write a script for a​n Action & Adventure, Comedy, and Drama Films.
2. Scope: Identify the timeline length.
3. Film: Work with stakeholders, and ensure filming & editing runs smoothly.
4. Release & Repeat​
