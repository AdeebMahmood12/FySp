# FySp
#### FySp stands for *"Find your Streaming Platform"* It is a site that allows one to search a movie/tv show and find if they are available on the most popular streaming platforms (eg: Netflix, Amazon Prime Video, and Disney+)

# How to use it
#### Using FySp is really easy, all you need to do is search for your desired movie/tv show in the search bar and select the correct one from the results.. Simple!!

# Libraries used
- Flask
    - I used *Flask* to merge all the Python functionalites with HTML. Basically, I used *Flask* to setup my backend for FySp.
- Requests
    - I used *requests* to make the API requests and fetch data from there and then do the necessary actions.

# API
#### A very vital part of this project was [TMDb API](https://www.themoviedb.org/documentation/api), it allowed me to make queries on thousands of movies/ tv shows and access their datas.

# Routes
#### There are five routes in FySp:
- 1) Movies `(/)`
    - This route is for searching the movies and choosing from a list of them
- 2) Results `(/results)`
    - This route shows the platform on which the selected movie is available on.
- 3) TV Shows `(/tv)`
    - This route is for searching tv shows and choosing from a list of them
- 4) Tv Results `(/tv_results)`
    - This route shows the platform on which the selected tv show is available on.
- 5) Credits `(/credits)`
    - This route just shows that the site uses TMDb API,
    but isnt endorsed by them.


# Reason behind making FySp
#### I made FySp because, I always found it a hassle to find out which streaming platform a certain movie was on.. There were times, when all of a sudden I decided to watch a movie but lost all the mood when I kept on looking for which platform that was on. I might not have lost the mood if I had all the 3 popular platform's subscriptions, I only have Netflix and once I dont find a certain movie/tv show there, I need to go on a voyage on finding which one it is on and then sign up for that particular platform.

# Disclaimer
#### This site uses the ***TMDB API*** but **is not endorsed or certified** by [TMDB](https://www.themoviedb.org/).
