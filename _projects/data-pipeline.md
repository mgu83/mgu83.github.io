---
layout: page
title: Pipeline @OVCARE
description: R, SQL, Data Analysis
img: assets/img/computer.png
importance: 1
category: work
giscus_comments: true
---

My summer project working as part of a bioinformatics team was the development of a data pipeline and graph algorithms. Although I technically worked under OVCARE, my work was going to be used by multiple principle investigators.

The data pipeline was split into two parts which I will discuss in general terms to abide by my NDA. First, different sources containing raw data was consolidated into one SQL database (DB). The difficulty with this step was that the different DB sources were from a variety of governmental and health official organizations, all with different languages and columns. Therefore, before I could consolidate all the data into my central DB, I had to filter, pivot and modify the entries so that they would all share common language. One idea I had was to use and continually train a language classifier, but I settled on some good old fashioned data transformations instead as most of the health organizations have pivoted toward using common language. 

To be continued...
