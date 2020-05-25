# [Project 1: Data Science Salary Estimator: Project Overview ](https://github.com/spstills23/ds_salary_proj)
* Created a tool that estimates data science salaries (MAE ~ $ 9K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* Built a client facing API using flask 

![](/images/avg_salary.jpg)
![](/images/avg_salary_heatmap.jpg)
![](/images/avg_salary_wordcloud.jpg)

# [Project #2 NCAA: Which Mascot Wins More? Python/SQL Class Final](https://github.com/spstills23/Final-Python-Project)
* For this project I asked the question of: "Does a college basketball team perform better when their mascot is Human or Non-Human in the NCAA basketball Tournament?"
* This report will take the results from every NCAA Tournamnet game since the 1985 season and compare whether teams with Non-Human or Human mascots win more.
* I first came across the data I needed on Kaggle. The link to the original is located here [https://www.kaggle.com/ncaa/ncaa-basketball](https://www.kaggle.com/ncaa/ncaa-basketball). 
This provided me with all the data that I needed from 1985 on. 
* There is really no background to this question that I am trying to answer other than the simple fact that I am curious of what the outome would be but I have a general hypothesis of what the end results will show.
* Within the report I will build dataframes and SQL databases to map out and show Team Total Wins, Team Wins merged with Mascots Names and finally catagorizing them into human and non-humans.
* We will count data sets to tally totals, graph with bar graphs and histograms as well as use some statistics and pie charts to see the results of our above questions.

![](/images/ncaa_wins.png)
![](/images/ncaa_pie.png)
![](/images/ncaa_conf_bars.png)

# [Project #3 Movie Recommendation Engine](https://github.com/spstills23/movie_recommendation_engine)
* Imported a movie dataset csv file and used sklearn and machine learning algorithms to recommend movies based off your inputed favorite.
* Engineered features to use in the algorithm: "overview", "keywords", "cast", "genres", "director".
* Combined the features into one string and used CountVectorize to convert the collection of text to token counts
* Used the Cosine Similarity to create a matrix showing the similar movies based off the features combined
* Created a function to be able to look through then index of movies to return a movie title that matches the similarity index.
* Returns the top 'n' movies based off your inputed 'favorite movie'.

![](/images/top_5.jpg)
