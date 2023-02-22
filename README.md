# TwitterAPI-Data-Processing-Pipeline
In this project, I apply the Python library, tweepy to extract data about all the daily tweets about a specified hashtag. The extracted data is stored in an AWS Redshift warehouse, and queries are then written to extract insights about the extracted data. Using airflow dags, the processes are automated to run once a day everyday.
