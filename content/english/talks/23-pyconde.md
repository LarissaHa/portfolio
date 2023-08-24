---
title: "Bringing NLP to Production (PyConDE Berlin 2023)"
date: 2023-02-01T12:40:00+06:00
# talks thumb
image : "images/talks/23-pyconde.jpeg"
draft: false
# description
description: "This is meta description"
# links
links:
  - label: "Slides"
    link: "https://github.com/LarissaHa/talks/tree/master/pyconde-2023"
  - label: "Video"
    link: "https://www.youtube.com/watch?v=GU8e2VgbqJ0"
  - label : "Source"
    link : "https://2022.pycon.de/program/VHNJ37/"
---

Models in Natural Language Processing are fun to train but can be difficult to deploy. The size of their models, libraries and necessary files can be challenging, especially in a microservice environment. When services should be built as lightweight and slim as possible, large (language) models can lead to a lot of problems.

All the way down from brainstorming the use case, receiving and cleaning the data, training and optimizing the model until service building, deployment, and quality monitoring, lots of important data science related decisions need to be made which in the end will influence the selection of deployment tools and infrastructure. And most often, those architectural decisions are rather long-term so they should be thoughtfully chosen in order to fit into the rest of the architecture.

With a recent real-world use case as an example, which runs productively for over a year and in 10 different languages, I will walk you through my experiences with deploying NLP models. What kind of pitfalls, shortcuts, and tricks are possible while bringing an NLP model to production? How can different model types and approaches influence architectural decisions? What are the most important questions to evaluate deployment platforms when there are several options to choose from?

In this talk, you will learn about different ways and possibilities to deploy NLP services. I will speak briefly about the way leading from data to model and a running service (without going into much detail) before I will focus on the MLOps part in the end. I will take you with me on my past journey of struggles and successes so that you don’t need to take these detours by yourselves. To follow this talk, you will need to know the basic concepts of deployment and MLOps, but no deeper knowledge of python or Natural Language Processing.

My goal is to enable you to ask important questions about deployment and going into production right at the beginning of every NLP project. I want you to be aware of problems that might occur so that working on NLP projects will be fun and not be overshadowed by deployment issues.