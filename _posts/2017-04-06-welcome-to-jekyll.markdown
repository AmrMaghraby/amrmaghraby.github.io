---
layout: post
title: GSoC'19 Week 8 - Week 11
date: 2019-07-16 13:32:20 +0300
description: #hhjhhh 
img: how-to-start.jpg 
---

## Deliverables for Week 8:

Currently in week 8 Arabic language is added but still facing some problems with HPC environment in the training phase.

## Week 9 - 10

Working on HPC and solving interior problems like input/output directories.
Commands To follow to launch OCR on videos : 
singularity shell -B /mnt/rds/redhen/gallina/home/aam193/Input:/mnt/ OCR-sif
python3 /opt/Convert.py
cd E2E-MLT
python3 eval2.py

## Notes before launching :
1) Directory called Input in same dir of image new-sif
2) the input file name must be input.mp4 (In case you need to change mp4 to any ther format it is easy to be done).


Project is done.
