# 🚀 Challenge: “Personalized Space Flight News Dashboard” (Using [spaceflightnewsapi.net](https://spaceflightnewsapi.net))

### Ready?

* Relax, try to make the best of the next ~90 minutes.
* We work on this together.
* It is more important to articulate decisions than finishing the whole application.

## Goal

Build a personalized space flight news dashboard where users can:

* Search for space flight articles on a specific topic
* Save favorite articles to a backend
* View saved articles in a separate section
* Implement pagination for better UX

Inspiration for design and understanding => [Minimalist Design](./design.jpeg)

## Approach

* before we start anything, explain your choice of architecture and tech stack
* use [https://spaceflightnewsapi.net/]()
* use **any** tool that can speed you up: a UI library, a framework, etc.
* this repository is set up with Nx. You are free to use it or NOT use it
* take shortcuts where needed, functionnality matters over style here. Features are ordered by priority
* do not bother with user authentication yet, assume there is only one user in your system

## Features

### Welcome screen

* Search bar to query news by keywords
* Display articles (title, summary, source, link, author)
* “Save” button to store articles in the backend
* Pagination for better user experience

### Saved articles

* Side navigation menu where users can access the welcome screen and the saved articles
* On a saved article page, display the article
* a "Delete" button to delete it
