---
layout: page
permalink: /amafr/
title: Advanced methodologies for the assesment of the fatigue response
description: Materials for the master course "Design of lightweight and composite structures"
nav: false
nav_order: 5
---

The doctoral course "Advanced methodologies for the assesment of the fatigue response" given to doctoral students at Politecnico di Torino covered
the application of Machine Learning models in the field of fatigue of metals.
I have had the pleasure to teach the class about "Fatigue & Machine Learning", where I could give an overview of machine learning methods for science has been given.

 {% pdf "/assets/pdf/AMAFR_MachineLearning&Fatigue_Part1&2.pdf" %}

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
