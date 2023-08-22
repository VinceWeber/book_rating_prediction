# Book Rating Prediction Project

![Project Banner](book_image.jpg) <!-- You can replace this with a banner/image relevant to your project -->

## Goodreads Book Ratings Analysis

Welcome to the analysis of the Goodreads-books dataset. In this project, we delve deep into the dataset to uncover patterns, insights, and train models to predict book ratings.

## Table of Contents

- [Installation](#installation)
- [Motivation](#motivation)
- [Questions](#questions)
- [Data Exploration](#data-exploration)
- [Training Models](#training-models)
- [Models Analysis](#models-analysis)
- [Results](#results)
- [Licensing and Authors](#licensing-and-authors)

## [Installation](#installation)

1. Clone this repository to your local machine using:
   ```bash
    git clone https://github.com/albinbrogialdi/book_rating_prediction/

2. Navigate to the project directory:
   ```bash
    cd book_rating_prediction
3. Create the anaconda environment using:
    ```bash
    conda create -n name_env_project --file ENV.txt
    ```
4. Activate the environment:
   ```bash
   conda activate name_env_project
   ```
    Replace 'name_env_project' by a custom environnement name.

## [Motivation](#motivation)

The Goodreads-books dataset provides a plethora of information about various books and their associated ratings. This project aims to use the CRISP-DM data mining methodology to analyze this dataset and understand the factors influencing a book's rating.

## [Questions](#questions)

To gain more insights about the Goodreads-books dataset, we sought answers to the following questions:

- Which authors wrote the most books?
- Who are the top-rated authors based on average ratings?
- How does the number of text reviews correlate with the average - rating of a book?
- Are there specific publishers that produce higher-rated books on average?
- How are the ratings distributed across different genres or - categories?
- How do newer books compare to older ones in terms of ratings and reviews?
- Which books are considered outliers in terms of ratings, reviews, or other metrics?

## [Data Exploration](#data-exploration)

- Number of Pages: Explored the distribution of book lengths.
- Ratings Count: Analyzed the popularity of books based on the number of ratings.
- Text Reviews Count: Investigated the relationship between the number of text reviews and average ratings.
- Publishers & Authors: Identified the most prominent publishers and authors in the dataset. ... [Other sub-sections from the Data Exploration section of the notebook]

## [Training Models](#training-models)

- Linear Regression: Implemented a foundational regression model to predict book ratings.
- Decision Tree & Random Forest: Trained hierarchical models to predict ratings.
- Gradient Boosting: Employed an advanced ensemble technique for predictions. ... [Other models and findings from the Training Models section of the notebook]

## [Models Analysis](#models-analysis)

A thorough analysis of the trained models, their performance metrics, and conclusions drawn from the analysis. [insights and results from the Models section]

## [Results](#results)

- The Random Forest (with GridSearch CV) and Gradient Boosting models have the lowest RMSE, indicating they have the smallest error in terms of predicting the book ratings.

- The highest R² value is associated with Gradient Boosting, indicating that this model explains the highest variability in the ratings.

- Decision Tree has the lowest R², making it the least effective model in explaining the variability in the data.

## [Licensing and Authors](#licensing-and-authors)

This project is licensed under the MIT License.

_Authors:_
- Brogialdi Albin (albin.brogialdi@edu.dsti.institute)
- Irrien Florian (florian.irrien@edu.dsti.institute)
- Sagnes Luc (luc.sagnes@edu.dsti.institute)
- Thabet Nader (nader.thabet@edu.dsti.institute)
- Weber Vincent (vincent.weber@edu.dsti.institute)



