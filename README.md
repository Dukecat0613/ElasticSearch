# ElasticSearch
There are 3 parts, the first one is crawling movie data from imdb such as movie poster, duration time, title, publish date etc, the second one is defining the elasticsearch mapping and store the data in elasticsearch, the final part is the front end which query the movie by elasticsearch query and suggestion.


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


## Presentation 
#### Auto-suggestion
<br><img src="https://github.com/Dukecat0613/Big-Data/blob/master/ImagesSet/Screen%20Shot%202017-02-26%20at%207.49.57%20PM.png"></src>

#### Sort 
<br><img src ="https://github.com/Dukecat0613/Big-Data/blob/master/ImagesSet/Screen%20Shot%202017-02-26%20at%207.50.16%20PM.png"></src>


#### Detail Information 
<br><img src="https://github.com/Dukecat0613/Big-Data/blob/master/ImagesSet/Screen%20Shot%202017-02-26%20at%2011.12.30%20PM.png"></br>
