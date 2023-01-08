---
title: "XAI meets Natural Language Processing (PyConDE Berlin 2022)"
date: 2022-04-13T12:40:00+06:00
# talks thumb
image : "images/talks/F3SZL3.png"
draft: false
# description
description: "This is meta description"
# links
links:
  - label: "Slides"
    link: "https://github.com/LarissaHa/talks/tree/master/pyconde-2022"
  - label: "Video"
    link: "https://www.youtube.com/watch?v=66A5D6NU17U"
  - label : "Source"
    link : "https://2022.pycon.de/program/F3SZL3/"
---

As people tend to be more aware of AI systems and their impact, AI ethics and transparency become more and more relevant. Explainable AI (XAI) is a not-so-new term to collect methods and techniques to make predictions of AI systems more understandable. Which data points build the basis for model fitting? How is the model trained, based on which premises and assumptions? Which decisions, which parameters lead to the optimized outcome? And, most important, which model weights and decision paths result in which predictions?

Today, there are various methods to apply XAI to AI systems. But when working with text data, it is not that easy to apply known methods out of the box to NLP systems. During pre-processing and while transforming text into numbers and vectors, we often lose the human-understandable parts. During modeling, we deal with so many data points, that single weights and words lose their meaning and their importance to the human eye. Thus, we cannot simply take well-known XAI techniques and apply them without a second thought. We need to be aware of the challenges, the specialties of text data, and the possible workarounds for the NLP area. 

In this talk, you will learn about local and global explanations, difficulties for modeling options and setups, useful libraries, such as SHAP or ELI5, and the importance of visual approaches. I will also show a real-world use case from my current work, with lessons learned and valuable outcomes. You will need to know the basic terms of Machine Learning and Natural Language Processing to follow the talk, but not the basics of XAI.

My goal is to encourage you to think about XAI directly from the beginning of each NLP project, as it will be central to transparency and acceptance. Also, you will learn about the right questions to ask to be sure about applications and expectations, so you can plan in terms of pre-processing, modeling, and explainability techniques.