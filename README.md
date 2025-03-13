# 🚀 Challenge: “Personalized Space Flight News Dashboard” (Using [spaceflightnewsapi.net])

### Ready?

* Relax, try to make the best of the next ~90 minutes.
* We work on this together.
* It is more important to articulate decisions than finishing the whole application.

## Goal

Build a personalized news dashboard where users can:

* Search for news articles on a specific topic
* Filter articles by category (business, tech, sports, etc.)
* Save favorite articles to a backend
* View saved articles in a separate section
* Implement pagination for better UX

## Approach

* before we start anything, explain your choice of architecture and tech stack
* use [https://spaceflightnewsapi.net/]
* use **any** tool that can speed you up: a UI library, a framework
* this repository is set up with Nx. You are free to use it or NOT use it
* take shortcuts where needed, functionnality matters over style here. Features are ordered by priority
* do not bother with user authentication yet, assume there is only one user in your system

## Features

### Rate Limits

* we use the free version of the API, for the next hour you are going to test a lot and maybe reach the limit of 100 requests per day
* let's discuss and solve that immediately!

### Welcome screen

* Search bar to query news by keywords
* Dropdown to filter by category (tech, sports, business, etc.)
* Display articles (title, description, source, link)
* “Save” button to store articles in the backend
* Pagination for better user experience

### Saved articles

* Side navigation menu where users can access the welcome screen and the saved articles
* On a saved article page, display the article
* a "Delete" button to delete it

