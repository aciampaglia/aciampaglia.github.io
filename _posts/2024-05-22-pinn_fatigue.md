---
layout: post
title: Tutorial on PINN applied to fatigue
date: 2024-05-22 08:57:00-0400
description: Tutorial on PINN applied to fatigue
tags: formatting jupyter
categories: sample-posts
giscus_comments: false
related_posts: false
featured: true
show: true
---

The doctoral course "Advanced methodologies for the assesment of the fatigue response" given to doctoral students at Politecnico di Torino covered
the application of Machine Learning models in the field of fatigue of metals.
I have had the pleasure to teach the class about "Fatigue & Machine Learning", where I could give an overview of machine learning methods for science has been given.

 {% pdf "../assets/pdf/amafr_course_slides_2024.pdf" %}

In this jupyter notebook you will find an introduction to Physics-Informed Neural Networks (PINN) with application to a toy problem.
Following, a dataset of fatigue experiments conducted on Additively Manufactured metals is provided to exercise with NN and PINN.

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/PINN_tutorial.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/PINN_tutorial.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

