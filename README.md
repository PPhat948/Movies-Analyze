# Top-Netflix-Movies-and-Series-Analyze-Project
## Overview
This is a project to practice my Python skills by cleaning the dataset and analyzing it by using visualization. It aims to find the top 10 Netflix Movies and Series in the year with the highest average rating.
## Tools & Librarys
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
## Dataset
The dataset that I used in this project is from Kaggle: MOVIES DATASET FOR FEATURE EXTRACION ,PREDICTION
https://www.kaggle.com/datasets/bharatnatrayn/movies-dataset-for-feature-extracion-prediction/code
## Steps in project
### 1.Import and cleaning data
- Drop column Gross that mostly data are missing values.
- Drop all rows with missing values.
- Convert data types.
- Clean text data.
- Extracting Director from Stars column.
- Extracting Start-Year and End-Year from Year column.
### 2.Analysis
- Distribution of rating
- Correlation heatmap
- Trend of Total Netflix Movies and Series-Series
- Average Rating Per years
- Top 10 Netflix Movies and Series-Series
### 3.Summmary insights
- Most rating are in 6-8.
- Number of released Netflix Movies and Series are highly increased after 2010
- Year with highest average rating are in 2018
- Top 10 Netflix Movies and Series in 2018 are:
  - Naui Ajusshi
  - My next guest needs no introduction with david letterman
  - Yeh Meri Family
  - Velhas Amigas
  - Pose
  - Car Masters: Rust to Riches
  - College Romance
  - Miseuteo Shunshain
  - One Strange Rock
  - SKY Castle

> [!NOTE]
> The average rating was not calculated before 2010 due to the low number of movies and series in that year.

> [!WARNING]
> The result in this project might be some incorrect due to dropping lots of data from missing values.
