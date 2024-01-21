# MoviePulse-Collaborate
![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/1848621c-acc6-4f40-a57c-76013ac3b422)  ![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/34ff05fc-f761-45dd-89de-87abf92265f3) ![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/d272ad21-6455-4926-ae03-8bba4be821f0) ![image](https://img.shields.io/badge/API-TMDB%20%20%7C%20OMDB-yellow)

**Description:**

MoviePulse-Collaborate is a content-based recommender system that suggests movies similar to the ones users like. Additionally, it performs sentiment analysis on user reviews for those movies.
The movie details, including title, genre, runtime, rating, poster, etc., are fetched using both the TMDB and OMDB APIs. For sentiment analysis, reviews given by users on the IMDB site are scraped using Beautiful Soup, and sentiment analysis is performed on those reviews.

**How to get API keys:**

1.Create an account at [The Movie Database (TMDB)](https://www.themoviedb.org/), and apply for an API key by navigating to the API link in your account settings.[TMDB API KEY]

2.Visit https://www.omdbapi.com/, navigate to the "API" section or go to https://www.omdbapi.com/apikey.aspx, sign up or log in, generate your API key by providing details and agreeing to the terms of use.[OMDB API KEY]

**How to run the project:**

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file using the command `pip install -r requirements.txt`.
3. Obtain your TMDB API key (as mentioned in the above section).
4. Replace YOUR_TMDB_API_KEY in places (line no. 15 and 29) of the static/recommend.js file and save.
5. Open your terminal/command prompt from your project directory and run the file main.py by executing the command `python main.py`.
6. Open your browser and type http://127.0.0.1:5000/ in the address bar.
 
 **How Cosine Similarity works:**

Cosine similarity is used to measure how similar two items are irrespective of their size. It calculates the cosine of the angle between two vectors projected in a multi-dimensional space. This is beneficial because even if two similar documents are far apart by Euclidean distance, they may still be oriented closer together.

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/c1210d0f-1a26-417e-ada2-27b51980a01e)

**Sources of the datasets:**

- IMDB 5000 Movie Dataset
- The Movies Dataset
- List of movies in 2018
- List of movies in 2019
- List of movies in 2020

  **Note:**
  
This project utilizes the TMDB and OMDB APIs for movie details and combines them for an enhanced movie recommendation experience. The information is used for educational and non-commercial purposes. Copyrights for the movie data remain with the respective data sources.

Feel free to explore, contribute, and customize MoviePulse-Collaborate for your needs!
