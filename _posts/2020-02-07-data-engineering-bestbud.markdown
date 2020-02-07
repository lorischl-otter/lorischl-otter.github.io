---
layout: post
title: Data Engineering - bestBud
date: 2020-02-07 01:00:00 -0600
description: A web app to recommend strains of medical marijuana based on symptoms
img: welcomebestbud.png
tags:
---



This week I was placed into my first cross-functional project team. We were tasked with creating a website that folks who are seeking recommendations for medical marijuana strains can utilize. Our role as the Data Science team was to come up with the predictive model to recommend strains based on user input, and return it to them.

For this project, I was in the role of Data Engineer. I was responsible for creating an API that would receive input from the user, via the backend, run it through the model our Machine Learning Engineer created, and return the five strain predictions to the backend to be returned to the user in the form of information about the strain. 

I also created a PostgreSQL database with all of the data hosted on ElephantSQL, though ultimately it wasn’t the best platform for our production database, which was created directly by the backend developer. 

I learned a lot about team work and communication across roles this week. It felt like I’ve been learning a new language the last 3 months (Data Science), and now was able to have a conversation in another language (Web Development) to come up with a final, polished product. 

We hit several snags and had to debug a lot of problems between teams, but we made it through. I was proud of us, and very excited to have been able to plug in a piece of this puzzle. 

The website is located https://bestbudapp.netlify.com/signup, (you can easily create a dummy profile to see the functionality) and it links to my API deployed [here](https://bestbud-strain-suggestions.herokuapp.com/), with documentation and testing capabilities for the API located [here on SwaggerHub](https://app.swaggerhub.com/apis-docs/lorischl-otter/bestBud-strain-suggestions/1.0.2).

Primary Skills/Platforms used: 
* Python
* Git Workflow
* Data Engineering
  - PostgreSQL Database creation in ElephantSQL
  - API creation
* Cross-Functional Team Communication
  - Primary contacts: Machine Learning Engineer, Backend Developer
* Heroku
* Flask

Skills/Platforms learned specifically for this project during project week:
* Postman for API testing
* SwaggerHub for API documentation
