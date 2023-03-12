# Predicting the revenue of the movies based on budget

### By - Rehan Mondal and Abheet Kansal 

##### Adapted from DSCI 100 Project by - Ming Zhang, Rehan Mondal, Caroline Lu and Jingwen Leng

### Summary

The entertainment industry has always been a profitable field, especially movies. However, with great profit comes great investment. Most modern-day movies require a budget of around 100 million dollars(1). It is crucial for investors/directors to have a general idea of how much profit they can make based on their investment. Thus, this project centers around studying the profitability of a movie before it is released, predicting revenues based on budget using Knn regression (since most movies fall under a general range of budget and there are rarely extreme outliers)

The question we will try to answer with our project is what is the revenue of a movie based on budget. The data set, which consists of 5000 movies from TMDB, will be separated into training and testing sets. Using budget as the predictor, the prediction of test set revenue will be made.

In the data set “TMDB 5000 Movie Dataset” (from "https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata"), revenues, budget, popularity are recorded for the 5000 movies listed in an excel format. Other columns are listed/included in the data set as well, however because they are written in json or not a significant predictor to the revenue, those columns will be filtered out. Revenues is defined as the total box income of the movie; budget is defined as the funding used for the production; Popularity numbers are built according to the TMDB model which consists of number of votes for the day, number of views for the day, number of users who marked it as a "favourite" for the day, Number of users who added it to their "watchlist" for the day, release date, number of total votes, and previous days score. We will discuss and analyze the correlation of each variable with revenue below.

### How to run

 - To replicate the analysis, install
[Docker](https://www.docker.com/get-started). Then `clone` this GitHub
repository and `cd` into the directory. Then run the following command at the command line/terminal
from the root directory of this project:

- `docker build --tag akrm-env .`

Followed by:
- `docker run --rm -p 8787:8787 -v "${PWD}":/home/rstudio -e PASSWORD="apassword" akrm-env`

- To open jupyter lab on the web browser `http://localhost:8787`

- Navigate to the work folder and then open Movie_Revenue_Predictor.ipynb from the Analysis folder

### Licenses

Predicting the revenue of the movies based on budget © 2023 by Abheet Kansal, Rehan Mondal is licensed under Attribution 4.0 International. If
re-using or re-mixing please provide attribution and link to this webpage.

### Acknowledgement

Mondal, R., Zhang, M., Lu, C., &amp; Leng, J. (2022). Predicting the revenue of the movies based on budget. Retrieved 2023, from https://github.com/rehan13/DSCI-100-Project-Group25.git 

Permission were take from all members of the DSCI 100 group on email by Rehan Mondal for re using this project.
