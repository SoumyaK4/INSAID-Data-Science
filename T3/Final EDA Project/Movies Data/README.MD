# Exploratory Data Analysis on 1000 Movies Data


# <u>Introduction</u>

- For many of us, **Entertainment is a major part of our lives** where we spend much of our free time to relax and chill.

- Watching movies in time-off is can be **good for your mental health and general wellbeing**.

- When we enjoy a good movie, we get lost in a movie and ***get a break from the everyday stressful life***.

<center><img src="https://images.unsplash.com/photo-1598899134739-24c46f58b8c0?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=856&q=80"></center>

- **IMDB** is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews.

- **Metascore** is the rating given by another movie rating company called Metacritic. However, **unlike IMDB, they get ratings from registered well known rating agencies** and calculates a weighted average of those ratings.

# <u>Problem Statement</u>

- Is there any secret formula for movie making in order to generate more Revenue ?

<center><img src="https://images.unsplash.com/photo-1517604931442-7e0c8ed2963c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"></center>

### **Scenario**

- In 2017, a production company ABC decides to produce movies that will earn the best in terms of revenue & popularity. 
- This company approaches SOUMYA, and asks him to come up with characteristics of movies that will help them achieve their purpose. 
- He is given the IMDB database of 1000 movies for the last 10 years (2006-2016). 
- His task is come up with the characteristics of movies that are well appreciated by critics and audience & earn the highest revenue.

 - What changes a director/producer must make in order to make movie a success in terms of revenue and popularity.

 - Making movies according to audience preferences in terms of genre,cast,runtime etc

 - What movies connect to global audience more.

 - How a positive rating and metascore impacts overall movie business

- Let's have a look.

# <u>Basic Info About The Data</u>

- The dataset is taken from the **IMDB**. It contains data of **1000 most popular movies(by IMDB rating)** for the **period 2006-2016**.

|Total Datapoints|TotalFeatures|Dataset Size|
|:--|:--|:--|
|1000|12|303 KB|

|Id|Feature|Description|
|:--|:--|:--|
|01|Rank|Movie Rank| 
|02| Title | Title of the movie|  
|03| Genre | The various Genre that the movie can be associated with| 
|04| Description| Short description about the movie|   
|05| Director| Director of the movie|
|06| Actors| Main actors in the movie|
|07| Year| Year in which the movie was released|
|08| Runtime (minutes)| Total movie playing time|
|09| Rating | Movie rating|
|10| Votes| Votes for the movie|
|11| Revenue (Millions)| Revenue by the movie (in millions)|
|12| Metascore| Is the score of the movie on the metacritic website by critics|

