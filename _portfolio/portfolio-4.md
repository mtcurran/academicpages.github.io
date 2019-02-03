---
title: "TrackStream"
excerpt: "A web app and API to stream music from your favorite movies and TV shows. (Fall 2016)<br/><img src='/images/projects_trackstream.png'>"
collection: portfolio
---

TrackStream is a web application that integrates the TuneFind API and YouTube API to allow users to search and stream songs from movie and TV show soundtracks. Using the TuneFind API allowed us to include descriptions of the scenes during which each song is playing, enabling someone to find a song even if the title, artist, or specific lyrics are unknown. The functionality of TrackStream is separated into its own API, which is called by the web server to return results to the front end for display.

As a team we utilized GitHub and Heroku to develop and deploy the HTML, CSS, and JavaScript for the project. The back end web server, which was my primary role, is written using Node.js and Express.js, while the front end makes use of Mustache.js for templating.

_Fall 2016 course project for INFO 253: Web Architecture_

[Project Link](http://trackstream.herokuapp.com){:target="_blank"} - [Web App Github](http://github.com/mtcurran/webarch-finalproject-trackstream){:target="_blank"} - [API Github](http://github.com/mtcurran/webarch-finalproject-trackstream-api){:target="_blank"}