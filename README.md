# big_data_analytics_project
This is the final project for the course on Big Data Analytics (Nov.-Dec. 2019). I analysed a dataset of AirBnb listings in NYC starting from April 2011. 

In particular:

 * I created a stratified version of the price feature and I trained some ML algorithms to classify it in terms of geografic and structural properties of AirBnb listings in NYC. The best performance belonged to a Random Forest Classifier, which has been fine-tuned;
 * A text analysis of the listing description has been done;
 * A time-series is studied. What is the busiest time of the year for AirBnb in NYC according to the reviews? Moreover, is there a seasonality in the results?

# Content 

* The folder with the raw data;
* The .ipynb containing the analysis of such data;
* A map of the city of NY in .png format.

### Important note

A connection to a PostgreSQL server has been implemented. Both raw and preprocessed data can be stored in a database, but this is left as an option to the user. Thus, every SQL-related command has been commented out in a markdown cell. Of course, the user shall not forget to insert his own credentials in the string connection, in case of need.
