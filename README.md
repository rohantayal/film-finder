**FILM FINDER**

You’ve caught up on your list of TV shows and movies and want to get recommendations for what to watch next, but aren’t sure where to look. In this project, you’ll use your knowledge of HTTP requests and asynchronous JavaScript to create a movie discovery app that will recommend random movies by genre. You’ll be able to choose from several genres, and like or dislike a movie to get another suggestion.

Before you begin, you’ll need to create an account on The Movie Database website. After you create your account and verify your email address, click on your user icon at the top right corner and navigate to the Settings page.

Screenshot of the settings page on the Movie Database website

On the Settings page, navigate to the API section and click on the link to Request an API Key to register as a Developer.

You’ll be asked to enter some personal information like your address and phone number. This is pretty common. Many APIs use this information to keep track of how their data is being used. As a part of your registration, you will also be asked to provide a URL for the site where you will be using this API. Here, you can list "https://codecademy.com". Check out these instructions if you need further assistance with registering for an API key.

After you finish this project, feel free to challenge yourself to continue building it out. For example, you might recommend TV shows instead of movies, or change the information you present about the recommended movies. The possibilities are endless. Next time you find yourself needing new content recommendations, you’ll know where to turn!


Additional features which I am looking to build:

1. Through the displayMovie() function in helpers.js use the DOM to rearrange the layout of information on the page. Try displaying different types of information like cast, or release date.

2. Create a way to store a user’s liked and disliked movies and display this list on the page.

3. Our API call inside of getMovies() returns many pages of results, but currently our program only randomizes results from the first page. To randomize our results even more, update getMovies() so that movies contains results from a random page instead of the first page.
