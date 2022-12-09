# Game Dataset Analysis with Python Pandas

Dataset from [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales).

### Libraries :
- numpy
- pandas 
- scipy
- math
- matplotlib
- seaborn
- plotly


## Description

- Read the data from csv and print first 10 data 
  > dataGame.shape shows 16598 rows and 11 columns in this dataset.
  ![first10row](/graphs/1.png)

- List of all columns with their data types and the number of non-null values in each column 
  > dataGame.info()
  => Their fields and data types are:

      Rank - Ranking of overall sales, integer
      Name - The games name
      Platform - Platform of the games release (i.e. PC,PS4, etc.), object
      Year - Year of the game's release, float
      Genre - Genre of the game ,object
      Publisher - Publisher of the game, object
      NA_Sales - Sales in North America (in millions), float
      EU_Sales - Sales in Europe (in millions), float
      JP_Sales - Sales in Japan (in millions), float
      Other_Sales - Sales in the rest of the world (in millions), float
      Global_Sales - Total worldwide sales, float
      
## Let's work on some graphs

- Game genres and count of games in these genres graph

  ![genresCount](/graphs/2.png)
  
- Sorting the number of games produced by years by showing the game genres

  ![ngames](/graphs/3.png)
  
- Sales comparison by genre

  ![salesCompG](/graphs/4.png)
  
- Platforms and their global sales

  ![globalSales](/graphs/5.png)
  
- Top 10 Game Publisher

  ![gamePublisher](/graphs/6.png)
  
- Global Game Sales

  ![gSales](/graphs/7.png)
  
## Summarize
  
- Global Sales Between 1980 & 2020

  ![a](/graphs/globalSale.png)
  
- Numbers
  
  ![a](/graphs/summarize.png)
