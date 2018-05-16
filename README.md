# crypto-prices
API of all cryptocurrency prices

## Endpoints

* [http://localhost:5005/api/categories](http://localhost:5005/api/categories) - Get all categories
* [http://localhost:5005/api/articles?category=news](http://localhost:5005/api/articles?category=news) - Get all articles from the news category
* [http://localhost:5005/api/article?url=an-article-url](http://localhost:5005/api/article?url=http://news.abs-cbn.com/news/05/16/18/god-help-the-philippines-senators-react-to-chinas-assurance-to-duterte) - Get an article

## Build Setup

``` bash
# install dependencies
$ npm install

# run app
$ npm start
```

## Built With

* [Express](https://expressjs.com/) - NodeJS Web Framework
* [X-RAY](https://github.com/matthewmueller/x-ray) - Web scraper
* [ABS-CBN](http://news.abs-cbn.com/) - Website scraped

## Acknowledgments

* Hat tip to anyone who's module was used
