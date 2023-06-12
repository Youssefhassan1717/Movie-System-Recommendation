<h1 align="center">Movie Recommendation Systems</h1>
<p align="center"><img src="movie-recommendation-image.jpg" alt="Movie Recommendation Systems" width="500px"></p>
<h2 align="center">Project Overview</h2>

This project aims to develop four different movie recommendation systems based on various algorithms and ideas. Each system offers unique approaches to provide personalized movie recommendations to users based on their preferences.
<h2 align="center">Recommendation Systems</h2>

    Top Movie Charts: The first system utilizes TMDB Vote Count and Vote Averages to create Top Movie Charts for both general and specific genres. The IMDB Weighted Rating System is employed to calculate ratings for sorting.

    Content-Based Recommenders: The second set of systems are content-based recommenders that leverage movie metadata and keywords. A filter is incorporated to prioritize movies with higher ratings and more votes, enhancing the accuracy of recommendations.

    Collaborative Filtering: The third system employs the Surprise Library to develop a collaborative filtering system using single value decomposition. This engine provides estimated ratings for a given user and movie, achieving an impressive RMSE of less than 1.

    Hybrid Engine: In the final system, a hybrid engine is created by combining ideas from content-based and collaborative filtering approaches. This engine delivers personalized movie suggestions to users based on internally calculated estimated ratings.

<h2 align="center">Data Sets</h2>

To build and train the recommendation systems, the following data sets are utilized:

    credits: Contains information about the cast and crew of each movie.
    keywords: Includes keywords associated with each movie.
    links: Provides links to external sources related to the movies.
    links_small: Contains a subset of links data for testing and validation.
    movies_metadata: Includes metadata and details for each movie, such as title, genres, release date, and more.
    ratings_small: Provides ratings given by users for various movies.

<h2 align="center">Getting Started</h2>

To use and test the movie recommendation systems, follow these steps:

    Clone this repository or download the project files.
    Install the necessary dependencies and libraries. Note that the Surprise Library is compatible with Linux operating systems.
    Upload the required CSV files (credits, keywords, links, links_small, movies_metadata, ratings_small) to your preferred development environment, such as Google Colab.
    Start working on the project, exploring and running the recommendation systems using the provided datasets.
    Customize and fine-tune the systems according to your specific requirements and explore additional dataset options to improve the recommendation accuracy.

<h2 align="center">Acknowledgments</h2>

We would like to acknowledge the contributions of various libraries and datasets used in this project. Their availability and accessibility significantly facilitated the development and evaluation of our movie recommendation systems.
<h2 align="center">Contributions and Issues</h2>

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue in the GitHub repository associated with this project. We appreciate any feedback and collaboration to enhance the movie recommendation systems.
<p align="center">
  <img src="popcorn-icon.png" alt="Enjoy Your Movies!" width="100px">
</p>

Note: For more detailed explanations and demonstrations of the project, you can refer to the following videos:

    Part 1: Movie Recommendation Systems
    Part 2: Movie Recommendation Systems
