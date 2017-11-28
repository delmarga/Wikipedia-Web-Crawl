# Wikipedia Web Crawl

This code uses Requests and Beautiful Soup to crawl Wikipedia, by opening an article and finding the first link in the article. After the first link is found, it will follow the first link of the next article until it reaches the [Psychology page](https://en.wikipedia.org/wiki/Psychology) or stops after more than 25 attempts.