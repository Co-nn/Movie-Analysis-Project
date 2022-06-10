# Movie Analysis Project
**Authors:** Connor McClain & Cooper McCombs

## Overview
The movie business is a multibillion dollar industry that estimated to have made roughly 36.8 billion as of 2021. On average, movies made in the U.S tend to make around 373.2 million worldwide. While money is important, popularity and ratings are what sustain a business. If a company is popular, money will follow. Using Python, we extracted data from movie websites to produce models on what makes movies well-liked among the public. Sorting the data by genre, we were able to showcase the most popular genres and their characteristics. 

## Business Problem
Microsoft is planning on creating a movie company and needs help to figure out what kinds of films they should produce. Using the data we found from IMDB (Internet Movie Database), TMDB (The Movie Database), and The Numbers website, we explored what types of movies were the most important to make. Then, proceeded to implement this data into graphs that conveyed the important traits of an average film. With this, we are able to portray to Microsoft that they should focus on popularity rather than profit.

## Data
 For this project, we used various sources of information to extract data that would represent my solution to Microsoft's problem. Then, we allocated this information on to different pandas dataframes based on its source. Not all data is clean and ready to go from the start. We had to remove all null values that would affect our models as well as clean through the columns of strings that we wanted to turn into integers (example: Production Budget). Our models correlated four different aspects of our solution for Microsoft: Genre based on highest average rating, genre based on highest average production budget, genre based on the ratio of the amount of movies already in that genre, and average runtime for each popular genre.

## Results
This graph represents the relationship between genre type and vote count score, showing the six most popular genres. The popular genres are colored orange to show that they are different from the other genres.
![](./Graphs/VoteCountScore.png)
This graph represents the average production budget of the six most popular genres.
![](./Graphs/Average_Budget_Cost_per_Genre.png)
This graph represents the amount of movies produced in each genre by percent.
![](./Graphs/Top_6_Most_Popular_Genres_to_Produce.png)
This graph represents the average runtime of each of the genres in popular genres.
![](./Graphs/Genres_by_Average_Runtime(minutes).png)

## Conclusion
From our data we were able to conclude:
- The top six most popular genres are: Action, Adventure, Comedy, Drama, Thriller, and Science Fiction
- That 67% of all movies Microsoft should produce should be at least one of the popular genres from above.
- Each movie should cost on average between $40 million and $140 million depending on the genre
- Each movie should be on average between 85 to 100 minutes long depending on the genre
## Future Work
We ran out of time, but some ideas we had to further our solution were:
- Comparing the popularity of adult rated movies to kid rated movies
- What are the best actors to use based on the genre of the movie
- What are the best directors based on the genre of the movie
comparing the popularity of a series of movies to a stand along movie
- Whether animated or real life films are more popular based on genre
## For More Information

## Repository Structure


