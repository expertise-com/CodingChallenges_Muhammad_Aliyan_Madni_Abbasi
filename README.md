# CodingChallenges

## Overview
This set of challenges are meant to cover a broad range of the types of problems. 
- Feel free to use any IDE you would like (I recommend [PyCharm](https://www.jetbrains.com/pycharm/))
- Feel free to use anything you would normally use during an average day on the job. *Please don't get help from a friend.*
- Each of these tasks should take no longer than an hour, however take as much time as you need to feel comforable with delivering them as if you were deploying to a production app.


## Python Flask/Django Web App Challage
### The base requirement:
- Create a [Flask](https://flask.palletsprojects.com/en/1.1.x/)/[Django](https://www.djangoproject.com/) web app that allows you to enter data via a web form
- Data should then be displayed in some way (on the same page or on another page)
- Data should be persistent. It’s up to you how you store the data, as long as it is persistent.

### Bonus:
- Allow the stored data to be manipulated (deleted, edited).
- An example use case for this could be a To-Do list app.

This is an open ended challenge. There are very few requirements and many possibilities! It doesn’t have to look pretty, as long as the functionality is there. Have fun with it!


## API Challenge
### The base requirement:
- Create a method to query your favorite API. (I recommend usuing [Python Requests](https://2.python-requests.org/en/master/) )

Lack inspiration? Here are some ideas to get you started:
- Make a Twitter digest or search for recommended books by your followers.
- Make a list of series being aired this week, using TheTVDB and/or movies premieres using TheMovieDB API.
- Pull a bunch of movie metadata using OMDb API or the TMDb API. TMDb seems more full featured and better supported.
- Check reddit for useful threads using the their API
- Pull your music playlists / metadata from Spotify API / Soundcloud API / YouTube API.
- Get a list of your Instagram photos via the Instagram API.
- Get a list of your friends' birthdays using the Facebook API.
- Do cool stuff with Google APIs: e.g. calendar, books, drive, Gmail, translate, Youtube, etc.
- Query the weather via OpenWeatherMap.
- Get fun facts from the [NumbersApi](http://numbersapi.com)

### Bonus:
- Write your own API that this challenge can read from. It can be as simple or complex as you'd like. Hint: Use that Web App challenge.


## Database Challenge
### The base requirement:
- Remember how we wanted to persist the data in the Web App challenge? Try out using a database to save the form entries. (I recommend [PostgreSQL](https://www.postgresql.org/))

### Bonus:
- Why not connect all three of these challenges into one. 
- Hint: Use Flask/Django to create an API to send and recieve the data from the Web Form, and save the data in a database.


## Extra Bonus
- If you know about GraphQL, try creating a GraphQL API
- Show off your front end skills a bit. 
- This is very open ended and just a bit of a chance to try to "WOW the judges". 
