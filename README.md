#Movie Recommender System with TMDB Dataset
This project implements a content-based movie recommender system using cosine similarity. It utilizes the TMDB (The Movie Database) dataset to recommend movies based on their features such as genre, cast, and crew.


#Overview
The movie recommender system employs a content-based approach to suggest similar movies to users. It extracts relevant features from the TMDB dataset, including genre, cast, crew, and keywords, and computes the similarity between movies using cosine similarity. The system then provides recommendations based on the input movie's features.


#Features
•	Recommends similar movies based on user input.
•	Utilizes cosine similarity for measuring movie similarity.
•	Implements a simple web interface for user interaction.
•	Deployment on Heroku for accessibility.


#Dependencies
The project relies on the following dependencies:
•	Python 3.x
•	Flask
•	Pandas
•	Scikit-learn
•	TMDB API (for accessing movie data)

#Setup and Installation
1.	Clone the repository:
bashCopy code
git clone <repository_url> 
2.	Install the Python dependencies:
bashCopy code
pip install -r requirements.txt 
3.	Obtain a TMDB API key from TMDB website and set it as an environment variable named TMDB_API_KEY.
4.	Run the Flask application locally:
bashCopy code
python app.py 
5.	Access the web interface at http://localhost:5000.


#Usage
1.	Enter the title of a movie in the input field.
2.	Click the "Get Recommendations" button.
3.	View the recommended movies based on the input movie.

