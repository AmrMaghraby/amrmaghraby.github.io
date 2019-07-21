---
layout: post
title: GSoC'19 Week 2 - 4
date: 2019-06-05 00:00:00 +0300
description: # Add post description (optional)
img: how-to-start.jpg # Add image post (optional)
tags: [Js, Conference] # add tag
---

## Deliverables for Week 2:

In week 2 I have implemented a Geo map successfully, which predicts the four coordinates of boundary boxes and the angle rotation.

This code has been trained on anther small data set (showcase model) Minist numbers to predict the numbers on rotated un-clear images.

## Deliverables for Week 3:

This I have implemented Shared Convolution Layer + making unpool part in the paper using the concept of bilinear interpolation (supported in python 2.7). Detection Branch Has been finished.

Tasks left till now: Recognition Branch.

## Deliverables for Week 4:

This week I have finished Recognition Branch which takes features as input and converts it to the expected tokens. After that new challenge unexpected meet me which requires me to prepare the dataset as the input is not a rectangle of four corners it is a polygon, so we need to preprocess the input (Next Week assignment).

Tasks left till now: preprocessing input to be rectangle instead of the polygon to learn Geo map to predict suitable boundary box.

Stay Tuned for more updates !!!!
