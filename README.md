# Analytics Projects
Some project work completed in the graduate courses

<h3>(1) <a href= "https://github.com/tnmasui/Projects/tree/master/InsideAirbnb" >Regression Model on Inside Airbnb data with Spark MLlib</a></h3>

In this project, I analyzed <a href="http://insideairbnb.com/get-the-data.html">"Inside Airbnb" data</a> to identify what factors affect property's ratings for the purpose of providing useful direction for users to choose better properties or for property owners to increase rating scores. To achieve that, I incorporated this huge data into HDFS, <a href= "https://github.com/tnmasui/Projects/blob/master/InsideAirbnb/Preprocess_Hive.hql">manipulated data with Hive</a>, and <a href= "https://github.com/tnmasui/Projects/blob/master/InsideAirbnb/Regression_MLlib_Scala.txt">developed regression model by MLlib Scala in Spark</a>. The following chart shows what factors are the most significant for ratings. 

<img src="https://github.com/tnmasui/Projects/blob/master/InsideAirbnb/IMG_Airbnb.jpg" height="350" width="600">

<h3>(2) <a href= "https://github.com/tnmasui/Projects/tree/master/TripAdviser" >Topicmodeling on User Review Data of TripAdviser with R</a></h3>

In this project, I analyzed <a href="http://kavita-ganesan.com/entity-ranking-data">TripAdviser's user review and rating data</a> and identified how users rate and comment on hotels by its location for the purpose of user's better hotel choice. To achieve that, I performed <a href= "https://github.com/tnmasui/Projects/blob/master/TripAdviser/TopicModeling.Rmd">topic modeling on user comments by hotel location</a> and found out which factors users appreciate or not. The following image shows the part of the result.

<img src="https://github.com/tnmasui/Projects/blob/master/TripAdviser/IMG_TripAdviser.jpg" height="350" width="600">

<h3>(3) <a href= "https://github.com/tnmasui/Projects/tree/master/IMDb" >Analyzing Movie Series Performance with IMDb Data by Python</a></h3>

In this project, we created a dataset with <a href="http://www.imdb.com/interfaces">IMDb plain text data files</a> by using <a href="http://imdbpy.sourceforge.net/"> the API (IMDbPY)</a>. Then, I <a href= "https://github.com/tnmasui/Projects/blob/master/IMDb/Series_Analysis.ipynb">analyzed how user ratings on movies differ across series numbers by using Python</a>. The original data has multiple tables, which includes such as a title table, a movie type table, a rating table, and a box-office table, so I joined those tables in this code. All the works from data pre-processing to data visualization are done in this code. The following image shows the result.

<img src="https://github.com/tnmasui/Projects/blob/master/IMDb/IMG_IMdB.jpg" height="350" width="600">
