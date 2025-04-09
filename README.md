# **Movie Prediction Analysis 🎬**

Movie prediction analysis using Python for exploring and modeling movie datasets.

## **Introduction 🎥**

Movies play a significant role in the entertainment industry, and their success is influenced by various factors, including genre, ratings, audience reception, and critical reviews. This project aims to analyze and predict factors that contribute to movie success by leveraging data-driven insights. Using a dataset containing detailed attributes of 16,000 movies, we perform exploratory analysis and build predictive models to forecast ratings and audience engagement.

This analysis focuses on trends in movie releases from **2021 to 2023**, including genre distribution, director trends, and the relationship between movie duration and ratings.

## **Data Overview 📊**

This dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/kashifsahil/16000-movies-1910-2024-metacritic) and comprises over 16,000 movies spanning from 1910 to 2024, providing a comprehensive foundation for analysis. The dataset includes detailed attributes such as movie titles, ratings, genres, directors, writers, and voting counts, enabling an in-depth exploration of movie trends and factors influencing success.

### **Columns Description**

| No | Column Name             | Description |
|----|------------------------|-------------|
| 1  | Index                  | Unique identifier for each movie |
| 2  | Title                  | Name of the movie |
| 3  | Release Date           | Release date of the movie (YYYY-MM-DD) |
| 4  | Description            | A brief summary of the movie's plot and significance |
| 5  | Rating                 | IMDb rating of the movie (e.g., 7.4) |
| 6  | No of Persons Voted    | Number of votes received on IMDb |
| 7  | Directed By            | Name of the director(s) of the movie |
| 8  | Written By             | Name of the writer(s) of the movie |
| 9  | Duration               | Duration of the movie in hours |
| 10 | Genres                 | Movie genres (e.g., Drama, Comedy, Mystery, Romance) |

## **Objectives 🎯**

- Analyze trends in movie releases from **2021 to 2023**.
- Identify the most popular genres and directors in recent years.
- Examine how movie duration has changed over time.
- Investigate the relationship between movie duration and ratings.
- Identify top-rated directors based on average movie ratings.

## **Methodology 🔍**

The analysis consists of the following steps:

1. **Data Cleaning and Preprocessing**: Handling missing values, correcting data types, and preparing data for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding key patterns, trends, and correlations.
3. **Data Visualization**: Creating visual insights into movie release trends, genre distribution, and rating variations.
4. **Statistical Analysis**: Evaluating the significance of relationships between movie attributes.

## **Key Questions Addressed 🧐**

- How has the number of movies released changed from 2021 to 2023?
- Which genres had the highest number of movies released each year from 2021 to 2023?
- Which director released the most movies from 2021 to 2023?
- How do movie ratings vary across different genres from 2021 to 2023?
- How has the average movie duration changed from 2021 to 2023?
- Which director had the highest average movie rating between 2021 and 2023?
- What are the mean, median, and standard deviation of movie ratings and durations from 2021 to 2023?
- Is there a significant relationship between movie duration and its rating for movies released from 2021 to 2023?
- How are movie durations distributed across different genres from 2021 to 2023?
- Was there a significant difference in average movie rating between 2021 and 2023?

## **Results and Insights 📈**

- The number of movies released showed a fluctuating trend between 2021 and 2023, with some genres gaining more popularity over time.
- Drama and Action were consistently among the most released genres, indicating their strong presence in the industry.
- Certain directors were particularly prolific, producing multiple films over this period.
- Ratings varied across genres, with Drama and Thriller films tending to receive higher ratings compared to Comedy and Horror.
- The average movie duration saw slight variations, with some genres exhibiting a tendency for longer films.
- Statistical analysis revealed a weak correlation between movie duration and rating, indicating that duration alone does not strongly influence audience perception.
- The difference in average ratings between 2021 and 2023 was analyzed to determine whether significant changes occurred in audience preferences.

## **Recommendations 💡**

1. **Enhance Genre Diversification** 🎭: Encourage a mix of genres to cater to diverse audience preferences.
2. **Leverage High-Rated Directors** 🎬: Focus on directors with consistently high average ratings to maximize movie success.
3. **Optimize Movie Length** ⏳: Adjust durations based on audience engagement trends to maintain viewer interest.
4. **Increase Marketing for Top Genres** 📢: Invest in promotional efforts for genres with historically strong performance.
5. **Data-Driven Release Strategy** 📅: Schedule movie releases in months with historically high audience turnout.

By implementing these strategies, movie studios can improve their chances of creating successful and well-received films.

1. **Optimize Genre Selection** 🎭: Focus on genres with high audience engagement.
2. **Director Selection Strategy** 🎬: Identify top-performing directors based on ratings.
3. **Movie Duration Planning** ⏳: Adjust movie length based on audience preferences.
4. **Statistical Insights for Marketing** 📢: Utilize data-driven findings to enhance movie promotion strategies.

## **Dependencies 📚**

- Python 3.12.7
- Jupyter Notebook

### **Libraries 🛠️**

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## **Author 👨‍💻**

Reza Syadewo
LinkedIn: [Reza Syadewo](https://www.linkedin.com/in/reza-syadewo-b5801421b/)