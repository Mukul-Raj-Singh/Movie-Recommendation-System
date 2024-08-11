# Movie Recommendation System
A Python-based movie recommendation system that leverages content-based filtering to suggest movies based on user preferences. The system uses TF-IDF vectorization and cosine similarity to identify and recommend movies that are similar to a user's favorite movie.

Features
Content-Based Filtering: Recommends movies based on the genre, keywords, tagline, cast, and director of the movies.
TF-IDF Vectorization: Converts movie features into numerical vectors for similarity calculations.
Cosine Similarity: Measures the similarity between movies to suggest the most relevant recommendations.
Spell Correction: Handles user input with closest spelling matching to ensure accurate movie title searches.
Top Movie Recommendations: Provides a list of the top similar movies based on user input.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/movierecommendationsystem.git
Navigate to the project directory:

bash
Copy code
cd movierecommendationsystem
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Download the dataset:

Ensure you have the necessary dataset by downloading it from here and placing it in the project directory.

Usage
Run the recommendation system:

bash
Copy code
python recommendation_system.py
Enter your favorite movie name when prompted.

View the top movie recommendations based on your input.

Example
bash
Copy code
Enter your favourite movie name: The Matrix
Top 10 Movies suggested for you:
1. The Matrix Reloaded
2. The Matrix Revolutions
3. Inception
4. ...
Requirements
Python 3.x
Pandas
NumPy
scikit-learn
Install all dependencies using the requirements.txt file.

Contributing
Feel free to submit issues, fork the repository, and make pull requests to contribute to the project.

License
This project is licensed under the MIT License - see the LICENSE file for details.

