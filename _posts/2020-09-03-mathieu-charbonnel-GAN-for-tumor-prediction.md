---
layout: post
title: "Mahieu Charbonnel, GAN for tumor prediction"
date: 2020-09-03
---
This project aims to predict brain glioma growth from a baseline MRI. It builds upon
proof-of-concept results using a extended version of Pix2Pix with pairs of 2D FLAIR
brain MRI tagged with time-lapse information. We intend to investigate the follow-
ing sophistications:
(1) Explore Pix2Pix on 3D MRI brain tumour images
(2) Explore the recent Edge-aware Ea-GAN architecture to improve prediction qual-
ity.
(3) Add a Time Predictor Model to improve growth prediction;
(4) Try using several input images from the same patient to predict an ulterior MRI;
The project builds on Andreas Zinonos’ work from last year as an Msc student.

