# Movie recommendation system

![movie-time](https://img.freepik.com/free-photo/lightbox-with-movie-time-text_23-2148470126.jpg?t=st=1718834447~exp=1718838047~hmac=05dcda21486ec2a5ef52dea19af3e96cc251c23785e2f28e627957d63e6b2bf8&w=826)

## Authors
[@tasfiakatha](https://github.com/tasfiakatha)

## Table of contents
- [Problem statement](https://github.com/tasfiakatha/Movie-recommendation-system/blob/main/README.md#problem-statement)
- [Data source](https://github.com/tasfiakatha/Movie-recommendation-system/blob/main/README.md#data-source)
- [Methods](https://github.com/tasfiakatha/Movie-recommendation-system/blob/main/README.md#methods)
- [Quick look at the results](https://github.com/tasfiakatha/Movie-recommendation-system/blob/main/README.md#quick-look-at-the-results)

## Problem statement

In today's digital streaming world, I often find myself overwhelmed by the sheer number of movies available on platforms like Netflix, Hulu, and HBO. This abundance of choices leads to a frustrating paradox where having too many options actually makes it harder for me to decide what to watch. I've noticed that I spend over 10 minutes on average just trying to pick a movie, and this time adds up quickly. According to a recent Nielsen Total Audience Report (Q1, June 2019), the average American spends about 7.4 minutes per day—or 45 hours per year—just deciding what to watch. This isn't just a minor inconvenience; it's a significant chunk of time that could be spent more productively or simply enjoying the movie itself.

My project aims to tackle this issue by developing a personalized movie recommendation system. The goal is to minimize the time I (and others) spend searching for something to watch. By using advanced algorithms and taking into account individual preferences, this system will provide tailored movie suggestions. This should help reduce the stress and indecision that comes with having too many choices, making the viewing experience more enjoyable.

Ultimately, I want to spend less time scrolling and more time watching great movies. This project is about creating a solution that enhances the way I interact with streaming platforms, allowing for quicker and more satisfying decisions about what to watch.

## Data source
- [MovieLens  25M dataset](https://grouplens.org/datasets/movielens/25m/)

I used MovieLens 25M dataset provided by GroupLens for this project. This dataset comprises of 25 million movie ratings and 1 million tag applications attributed to 62,000 movies and 162,000 users. Additionally, it includes tag genome data with 15 million relevance scores across 1,129 tags. I mainly used the movies and ratings csv files for my project.

## Methods
**Data preprocessing**: Clean and preprocess the datasets to address missing values, outliers, and inconsistencies in movie titles or other features. This step ensures the quality and reliability of the data for accurate analysis and modeling.

**Data integration**: Combine the movie details and user ratings datasets using common identifiers (e.g., movie ID). This integration creates a comprehensive dataset that includes both movie attributes and user interactions, providing a robust foundation for analysis.

**Model development**: Implement various recommendation algorithms, including collaborative filtering (user-based and item-based), content-based filtering, and Item-item Recommendations with k-Nearest Neighbors. These models will leverage the integrated dataset to generate personalized movie recommendations.

**Model evaluation**: Evaluate the performance of the recommendation system using metrics such as precision, recall, and mean average precision (MAP). These metrics will help assess the accuracy and effectiveness of the recommendations, ensuring the system meets the desired standards.

## Quick look at the results
Distribution of movie ratings in the dataset

![image](https://github.com/tasfiakatha/Movie-recommendation-system/assets/120822849/6576d503-6b30-4f4e-9fe6-bd08b8245ed8)

Distribution of movies by genre

![image](https://github.com/tasfiakatha/Movie-recommendation-system/assets/120822849/da03df44-b8ee-4a94-a7d2-45bd05134ba9)


The Shawshank Redemption (1994), The Godfather (1972), and The Usual Suspects (1995) are the highest rated movies using bayesian average. This reflects more accurate popular movies.

![image](https://github.com/tasfiakatha/Movie-recommendation-system/assets/120822849/00586c33-8007-4bb1-a5bd-9e1b7024a8ba)

Battlefield Earth (2000), Gigli (2003), and Glitter (2001) are the worst rated movies with below 2.0 ratings

![image](https://github.com/tasfiakatha/Movie-recommendation-system/assets/120822849/08ced426-79b1-4f20-8483-d376a4670546)

Here are 10 movies that users with similar taste to those who enjoyed Toy Story (1995) have also rated highly using collaborative filtering method -

![image](https://github.com/tasfiakatha/Movie-recommendation-system/assets/120822849/7766a72f-b4d3-481a-b8bd-f6ba239f34f4)


