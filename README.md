# Recommendersystem with Spark, Elastic Search and Flask for MovieLens

This project is a sideProject to clone Netflix with MovieLense Data and TMDB API
* Top N unrated movie recommender for user

### Enviroment
* Elasticsearch 5.3.0  
* Spark-2.3.1-bin-hadoop2.7  
* ElasticSearch-hadoop-5.3.0  

### Directory
sc\_with\_elastic : spark context with elasticsearch  
spark\_session : spark session

### Execution
1. Install Spark, ElasticSearch and configure enviroment.
2. Download the data ml-latest from grouplens site
3. pip install -r requirements
4. cd sc_with_elastic
5. Configure server.py, start.sh
6. ./start.sh

### Execution with ElasticSearch
1. create index  
IP:PORT/index/movielens  
2. save data to ElasticSearch  
IP:PORT/save_to_es   
3. search data from ElasticSearch 

### Acknowledgement
* [GroupLens, MovieLense](https://grouplens.org/datasets/movielens/)  
* [TMDB API](https://www.themoviedb.org/documentation/api?language=en-US)
