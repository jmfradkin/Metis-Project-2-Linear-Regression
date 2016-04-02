# Metis-Project-2-Linear-Regression

*Project 2 of Metis Data Science Bootcamp.* Problem statement below:  

Using information we scrape from the web, can we build linear regression models from which we can learn about the movie industry?
___

I chose to focus on movies "Based on a true story" to determine which features predict success, as measured by Worldwide Gross. Using BeautifulSoup, I scraped movie data from IMDB.com, Boxofficemojo.com, and Thenumbers.com on the following features:

1) MPAA Rating (G/PG/PG-13/R)  
2) Runtime  
3) IMDB Score  
4) Opening # Theaters (Domestic)  
5) Opening Gross (Domestic)  
6) Total # Theaters (Domestic)  
7)Total Gross (Domestic)  
8) Peak movie season (May, June, July, November, December are highest grossing months)  
9) Budget  
10) Genre: Action, Adventure, Biography, Comedy, Crime, Documentary, Drama, Family, History, Horror, Music, Mystery, Romance, Sport, Thriller, War, Western  

I performed OLS Regression using StatsModels and eliminated features that had an insignificant effect on the response variable by evaluating the p-values and R^2 value of the model.

---

###Files

1) `movies.csv` contains the data scraped from the web  
2) `web_scraping.ipynb` shows the process of scraping movie data from the 3 websites  
3) `model_testing.ipynb` shows the process of evaluating linear regression models and plotting feature relationships  

The project **blog post** can be found [here](https://jamiefradkin.wordpress.com/2016/01/30/metis-project-2-predicting-box-office-performance/).

