---
layout: post
title: GSoC'19 Week 1
date: 2019-05-29 00:00:00 +0300
description: # Add post description (optional)
img: how-to-start.jpg # Add image post (optional)
tags: [Programming, OCR , Data Science] # add tag
---

## This is weekly Report about my work and my progress in OCR on videoes project.

## Notes from community bounding period :

1. Red Hen Lab students recieved mail announcing that we will access HPC server to train our model and launch our project on it at the end.
2. We recieved account on CASE CWRU to be able to sign in on HPC using VPN any client software.

## Deliverables for Week 1:

Divided project into the following sections : 

1. Shared Convolution Network (used for extraction features which will be used both text detection and text recognition).

2. ROI Rotate: Mid-layer takes input features extracted from the shared conv network and applies an automated affine transformation (Rotate - shaer - scale - transition).

3. Detection Branch:  Contains anther CNN which predicts the location of text in a 2d matrix (Score Map) which uses anther 2d matrix as an auxiliary matrix called Geo-Map (predicts the corner of predicted boundary box  PLUS the angle of rotation of the text from the horizontal line).

4. Recognition Branch: Contains CNN attached with BLSTM of sequence length = 20, takes input features extracted from shared convolution layer and pass it through CNN then through BLSTM to extract the recognized tokens.

In week 1 I have implemented a score map successfully.
I will post my progress here. Stay Tuned !



