---
layout: page
title: mealio
description: Python (Beautiful Soup & Selenium), TensorFlow, Swift, SQL, Data Normalization
img: 
importance: 3
category: fun
---

[Project Link](https://github.com/mgu83/web-scrape)

Note that I am expanding this idea for my relational databases class and per academic guidelines, I have had to take it down as I work on it.*

As an avid grocery deal chaser, I wanted to find an easier way to collate all the best deals from my favourite grocery stores. I specifically wanted a way to compare grocery prices between my two closest grocery stores - NoFrills and Safeway. Hence, the idea for mealio (name is still in progress was born). 

The first thing I did was build a web scraper for the two grocery stores in mind. I specifically made the scrapers flexible so that I can scrape flyers from different store locations too. Now that I had all the data, I wanted to expand on the idea and work on interface to display this information.

That is when I started working on the app in Swift. I am currently working on that as well as a ML model to help recommend and predict what will be on sale in the next few weeks. 

*Here is some of the progress I have made for my class. Below is an Entity Relational Model that I created for the database that will store all the data scraped. Note the different constraints that I placed on different entities 

<div style="text-align: center;">
    <img src="/assets/img/er_diagram.png" alt="ER diagram" style="width: 70%; height: auto; display: block; margin: auto;"/>
</div>

I had to perform BCNF normalization to each of the tables to make the schema lossless. 

Currently working on the accompanying web app that queries data from my SQL database. 