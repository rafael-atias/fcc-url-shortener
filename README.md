# API Project: URL Shortener Microservice for freeCodeCamp

This is my implementation of the FreeCodeCamp's [URL shortener project](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/url-shortener-microservice ). The repository is a fork of the [Freecodecamp boilerplate repo](https://github.com/freeCodeCamp/boilerplate-project-urlshortener/ ).


### User Stories

1. I can POST a URL to `[project_url]/api/shorturl/new` and I will receive a shortened URL in the JSON response. Example : `{"original_url":"www.google.com","short_url":1}`
2. If I pass an invalid URL that doesn't follow the valid `http(s)://www.example.com(/more/routes)` format, the JSON response will contain an error like `{"error":"invalid URL"}`. *HINT*: to be sure that the submitted url points to a valid site you can use the function `dns.lookup(host, cb)` from the `dns` core module.
3. When I visit the shortened URL, it will redirect me to my original link.


#### Creation Example:

POST [project_url]/api/shorturl/new - body (urlencoded) :  url=https://www.google.com

#### Usage:

[\[this_project_url\]/api/shorturl/4283b0db37ea](https://rafael-atias-fcc-url-shortener.glitch.me/api/shorturl/4283b0db37ea)

#### Will redirect to:

https://www.freecodecamp.org/

#### Repository

[Link to Github repo here](https://github.com/rafael-atias/fcc-url-shortener)