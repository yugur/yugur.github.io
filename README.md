# Yugur Online Dictionary
## About
The Yugur Online Dictionary is an open-source project aiming to build a dictionary targeted at the preservation and research of indigenous and endangered languages. The project is currently split into two parts: a web app built with React.js and a RESTful API built in Go.

## Source
The source code and information such as licensing, installation instructions and changelogs can be found on [GitHub](https://github.com/yugur). 

Fancy-looking stats for the API are generated periodically [here](api-stats/index.html).

## Live Demo
A live demo of the web app is running at [http://128.199.134.221:3000](http://128.199.134.221:3000). Networking with the API may be down so it is currently also exposed [here](http://128.199.134.221:8080/) and serves simple demo pages for the auth process. Some example calls:
* [Check that the server is running](http://128.199.134.221:8080/status)
* [Get the entry for "dog"](http://128.199.134.221:8080/entry?q=dog)
* [Get the entire dictionary](http://128.199.134.221:8080/fetch)
* [Search by letter](http://128.199.134.221:8080/search-letter?q=c)

## Development
Development is managed through a publicly accessible [Trello board](https://trello.com/b/jMzGDNag/yugur-dictionary-app).

## Artefacts
There are a number of publicly accessible project artefacts available [here](https://drive.google.com/open?id=0ByT4L7eSmJWtZXIwQV8xX2U2VFU).
