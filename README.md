# My Movie Journal

## Project Description
"My Movie Journal" is a platform designed to record movies that match personal preferences, similar to a daily diary. It functions like a music playlist but for movies, allowing users to track and manage their favorite films.

## Data Preprocessing
The original data is from Kaggle, consisting of two CSV files: one with (movie_id, movie_title, genre) and another with (user_id, movie_id, user_rating, timestamp). Due to the large number of movies, only 100 were randomly selected for the project. The release date attached to the movie titles was removed and stored in a dictionary called `movie_date`. The average rating for each movie was calculated based on user ratings. A DataFrame was created containing movie titles, genres, and ratings.

[Original Data Link](https://www.kaggle.com/code/ayushimishra2809/movie-recommendation-system/input?scriptVersionId=31040795)

## How to Use

1. Log in to use the service.
2. Search for the desired movie on the main screen.
3. Alternatively, select a genre to view all movies within that genre.
4. The searched movies can be sorted by highest rating or most recent release date.
5. Click on a favorite movie to save it to the favorites list.
6. Go to the main screen and click on the favorites view to see the saved movies.

### Step 1
- Welcome message on start
- Login screen (ID and password stored in the file)
- Password is hidden with *, and an error message is shown if login fails
- Successful login

### Step 2
- Search for a movie like 'Blended' on the main screen
- If the movie is not found, an error message is shown
- If the movie is found, it is displayed with the title, genre, and rating

### Step 3
- Select a genre on the main screen
- Search for movies in the Romance genre

### Step 4
- Choose to sort by rating or date
- Sort by highest rating
- Sort by most recent release date

### Step 5
- Click on a movie to add it to favorites
- Movie details (title, genre, rating) are saved in `recommend.txt`

### Step 6
- Click on favorites view to check the saved movies


![image](https://github.com/ai-cho/movie_recommend_GUI/assets/120773889/453f930e-12df-4d50-acd9-2e56c971cdf9)

![image](https://github.com/ai-cho/movie_recommend_GUI/assets/120773889/d2706133-ca13-4656-b0db-45a6145c14f2)

![image](https://github.com/ai-cho/movie_recommend_GUI/assets/120773889/8e243f3a-2da5-4888-a56a-8f0b393a14cf)

![image](https://github.com/ai-cho/movie_recommend_GUI/assets/120773889/021898a5-8323-4fba-af72-e9f86d94c6bb)

![image](https://github.com/ai-cho/movie_recommend_GUI/assets/120773889/5386a492-e05e-4385-8f70-8ab0ce9b2c71)
