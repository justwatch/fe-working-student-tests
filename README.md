# Movie List task

## Problem
The most pressing need for all movie lovers is to know which movies are playing at the cinema. 
They also want to read reviews to decide which of these movies they want to watch.
Your job is to solve that problem with an application that allows users to bookmark currently 
playing movies. For this, you are supposed to use the API provided here: https://api.themoviedb.org.
As someone familiar with the JustWatch Culture, you know that you don't need to build the 
perfect application; you need to make one that provides value to your customers first.

## Objectives
Build a UI that:
  * Displays a list of currently playing movies.
  * Allows the user to bookmark a subset of these movies.
  * Saves the bookmarked films.
  * Enables a user to click on a title to see its details and reviews.

At JustWatch, we are working with ReactJS, but you can use a frontend framework you are 
familiar with. The same is true for CSS/Styling frameworks. Images can be placeholders 
if not available.

In general, what is important to us is your familiarity with software development concepts.

## How to deliver your solution
We expect a pull request in the repository we provided you from your branch to main. 
Please include a README describing the steps and decisions you took regarding 
architecture, technologies, and other aspects of the service you feel are important.

We don't expect everything will be 100% done and polished; feel free to prioritize.

We expect you to work two to three hours on this project. If you can not finish 
this assignment in time, add a few comments in the README about what is missing 
and your estimate of how long it would take to complete it.

## Resources
  * API KEY: 7cbf8d07a0c09237c3c08d8e5127fd63
  * You will get a list of the currently playing movies at: 
    https://api.themoviedb.org/3/movie/now_playing?api_key=<API_KEY>&language=en-US
  * Documentation for this endpoint is at:
    https://developers.themoviedb.org/3/movies/get-now-playing
  * You will get the reviews of your selected movie at:
    https://api.themoviedb.org/3/movie/<movieId>/reviews?api_key=<API_KEY>&language=en-US
  * Documentation for this endpoint is at:
    https://developers.themoviedb.org/3/movies/get-movie-reviews
  
