# MoviePulse-Collaborate
![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/1848621c-acc6-4f40-a57c-76013ac3b422)  ![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/34ff05fc-f761-45dd-89de-87abf92265f3) ![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/d272ad21-6455-4926-ae03-8bba4be821f0) ![image](https://img.shields.io/badge/API-TMDB%20%20%7C%20OMDB-yellow)

**Description:**

MoviePulse-Collaborate is a content-based recommender system that suggests movies similar to the ones users like. Additionally, it performs sentiment analysis on user reviews for those movies.
The movie details, including title, genre, runtime, rating, poster, etc., are fetched using both the TMDB and OMDB APIs. For sentiment analysis, reviews given by users on the IMDB site are scraped using Beautiful Soup, and sentiment analysis is performed on those reviews.

**Home Page**

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/e6f9afcf-0dad-475c-8f1d-41ce85c31468)

**Auto-complete example**

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/1b854430-5379-4a30-9ad3-71fa18aacb84)

**Main Content**

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/39f1ff47-8ff8-45ba-99fa-b71ed838f07a)

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/602d3b4a-e98c-4afe-bbe7-5656ee14d7d9)

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/f0af3a32-41a6-422b-a004-a3dbcdc50835)

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/7cbc623e-b764-44a9-9cae-3d5824fc605e)

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/9cc25335-3c7d-4794-9bc6-16ec37cf712a)



# How to get API keys:

1.Create an account at [The Movie Database (TMDB)](https://www.themoviedb.org/), and apply for an API key by navigating to the API link in your account settings.[TMDB API KEY]

2.Visit https://www.omdbapi.com/, navigate to the "API" section or go to https://www.omdbapi.com/apikey.aspx, sign up or log in, generate your API key by providing details and agreeing to the terms of use.[OMDB API KEY]

# How to run the project:

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file using the command `pip install -r requirements.txt`.
3. Obtain your TMDB & OMDB API keys (as mentioned in the above section) and replace "YOUR_API_KEY" in Preprocess/preprocessing_4.ipynb [OMDB API KEY].
4. Replace "YOUR_API_KEY" in places (line no. 15 and 29) of the static/recommend.js and in Preprocess/preprocessing 3.ipynb file and save.
5. Open your terminal/command prompt from your project directory and run the file main.py by executing the command `python main.py`.
6. Open your browser and type http://127.0.0.1:5000/ in the address bar.

# Similarity Score :

How does the system identify which item closely matches the user's preferences?

This is determined by similarity scores, numerical values ranging from zero to one. These scores gauge the likeness between two items based on their text details. Essentially, the similarity score measures how similar the textual information of two items is, and this comparison is achieved through a method known as cosine similarity. The higher the similarity score, the more alike the text details of the two items are considered to be.
 
 # How Cosine Similarity works:

Cosine similarity is used to measure how similar two items are irrespective of their size. It calculates the cosine of the angle between two vectors projected in a multi-dimensional space. This is beneficial because even if two similar documents are far apart by Euclidean distance, they may still be oriented closer together.

![image](https://github.com/AhteshamKamal/MoviePulse-Collaborate/assets/84683903/c1210d0f-1a26-417e-ada2-27b51980a01e)

# Sources of the datasets:

- IMDB 5000 Movie Dataset
- The Movies Dataset
- List of movies in 2018
- List of movies in 2019
- List of movies in 2020

# Note:
  
This project utilizes the TMDB and OMDB APIs for movie details and combines them for an enhanced movie recommendation experience. The information is used for educational and non-commercial purposes. Copyrights for the movie data remain with the respective data sources.

Feel free to explore, contribute, and customize MoviePulse-Collaborate for your needs!
