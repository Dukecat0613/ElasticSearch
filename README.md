# ElasticSearch
There are 3 parts, the first one is crawling movie data from imdb such as movie poster, duration time, title, publish date etc, the second one is defining the elasticsearch mapping and store the data in elasticsearch, the final part is the front end which displays the movie.


## How to run?
Firstly, starting crawling data
```
scrapy crawl imdb_spider
```
Secondly, seting up Flask application on the Front folder
```
export FLASK_APP=webmovie.py
```
```
flask run
```
Finally, enter the ip in the browser
```
localhost:5000
```
