# Spotify-Attributes-EDA-Popularity-Prediction
The objective of this project is to perform Exploratory Data Analysis (EDA) on the song attributes of a Spotify dataset and build a model to predict the popularity of songs using Python.

## Objective

The objective of this project is to analyze the Spotify dataset and explore the relationship between different song parameters and popularity. Using machine learning algorithms, we aim to predict the popularity of songs based on their attributes. The goal is to provide insights to web developers and streaming services like Spotify, enabling them to identify popular songs and improve their recommendations to users.
Scope

## The scope of this project includes:

   Performing data wrangling to clean the dataset and handle missing values.
   Conducting Exploratory Data Analysis (EDA) to identify correlations between song attributes and popularity.
   Building a predictive model using the Decision Tree algorithm to predict song popularity.
   Evaluating the model's accuracy and discussing the findings.

## Dataset

The selected dataset is the 'Spotify Dataset 1921-2020', which consists of approximately 170,000 songs released between 1921 and 2020. The dataset contains various parameters related to the songs, such as acousticness, danceability, energy, explicit content, instrumentalness, key, liveness, loudness, popularity, tempo, valence, and year.
Methodology and Concepts Used

##  Resources
The project utilizes Python and several libraries for data analysis, visualization, and machine learning. The main libraries used are:

   NumPy and pandas for data manipulation and operations.
   Matplotlib and Seaborn for data visualization.
   Scikit-learn (sklearn) for machine learning algorithms.

## Algorithm
The Decision Tree algorithm is used to build the popularity prediction model. The algorithm splits the training dataset based on parameters like entropy, Gini impurity, and information gain, iteratively creating an optimal predictive model.
Results, Findings & Discussion

## Methodology
The project involves three main steps: data wrangling, exploratory data analysis, and prediction.

   Data Wrangling:
       The dataset was cleaned by removing duplicate rows and unnecessary columns.
       Missing values were handled, resulting in a clean dataset without duplicates or missing values.

   Exploratory Data Analysis (EDA):
       Correlation between song features and popularity was analyzed using heatmap and correlation plots.
       Artists were examined to identify the most popular ones on Spotify.
       The occurrence of explicit content and its relationship with popularity was explored.
       The influence of musical keys on popularity was studied.
       Relationships between popularity and various features (acousticness, liveness, duration, loudness, valence, instrumentalness, tempo) were analyzed.
       The change in popularity over the years was observed.

   Prediction:
       A predictive model was built using the Decision Tree algorithm to predict song popularity.
       Various song attributes were considered as input features for the model.
       The model's accuracy was evaluated, and predictions were made based on the trained model.

## Conclusion
Based on the analysis, several insights were obtained regarding the relationship between song attributes and popularity. The findings can help in understanding the factors that contribute to the popularity of songs and improve recommendations for streaming services.

For detailed information, refer to the project report and the code files in this repository.
