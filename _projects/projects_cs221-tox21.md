---
layout: post
category: projects
title: Modeling and Prediction of Drug Toxicity from Chemical Structure
setting: Stanford CS 221, Fall 2017
team: Joyce Kang, Rifath Rashid
mentors: Anna Wang
excerpt: |
  Humans are exposed to many different chemical compounds throughout the life course from sources including food, cleaning products, and drugs. In 2014, the [Tox21 data challenge](https://tripod.nih.gov/tox21/challenge/) was launched by the National Center for Advancing Translational Sciences (NCATS) at the U.S. National Institutes of Health (NIH) to better understand the potential of compounds to disrupt biological pathways in possibly toxic ways. The Tox21 library comprises over 10,000 chemical compounds, and data was generated from biological assays measuring each compound’s effect on nuclear receptor signaling and cellular stress pathways.

  We trained a 5-layer neural network, achieving a relatively high accuracy of 0.79 and AUC of 0.78 on the validation set. Additionally, by computing the gradient of prediction probabilities with respect to out input features, we were able to recover insights about structure-activity relationships. Carbonyl groups (e.g, ketones, esters, and carboxylic acids) were most predictive of toxicity, while the presence of many aromatic rings tended to be a negative predictor of toxicity.
thumbnail: https://ncats.nih.gov/files/tox21-DNA-260px.jpg
media:
  - type: github
    url: https://github.com/bentyeh/tox21_cs221
    name: Code
  - type: file
    url: https://drive.google.com/open?id=1z_RtsuLq-luNN4DpRNiYXzcOCEv4-YNJ
    name: Poster
---