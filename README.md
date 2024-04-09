

# Movie Recommendation System

## Overview
This is a simple movie recommendation system that takes two inputs from the user: genre of the movie and number of recommendations desired, and provides the output in the form of a table.

## How to Use
1. Clone or download the repository to your local machine.
2. Install the required dependencies by running:
    ```
    pip install -r requirements.txt
    ```
3. Run the `movie_recommendation.py` script:
    ```
    python movie_recommendation.py
    ```
4. Follow the prompts to input the genre of the movie and the number of recommendations desired.
5. The system will generate a table displaying the recommended movies based on the inputs provided.

## File Structure
- `movie_recommendation.py`: Main script file containing the movie recommendation logic.
- `requirements.txt`: File listing the required Python dependencies.

## Input Requirements
- Genre of the movie: Enter the genre of the movie for which you want recommendations. Options include Action, Comedy, Drama, Horror, Romance, Sci-Fi, Thriller, etc.
- Number of recommendations: Enter the number of movie recommendations you want to receive. The system will provide this many recommendations based on the input genre.

## Output Format
The system will output the recommended movies in the form of a table, including details such as movie title, release year, and rating.

```
| Title                | Year | Genre       | Rating |
|----------------------|------|-------------|--------|
| Movie 1              | 2020 | Action      | 8.5    |
| Movie 2              | 2018 | Action      | 7.9    |
| Movie 3              | 2019 | Action      | 8.2    |
| ...                  | ...  | ...         | ...    |
```

## Additional Notes
- This system uses a simple recommendation algorithm based on user input. For more advanced recommendation techniques, consider exploring collaborative filtering or content-based filtering methods.
- The movie dataset used for recommendations can be customized or expanded to include more movies and genres for better recommendations.
