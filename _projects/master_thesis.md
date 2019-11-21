---
title: "Flood-Water Estimation through Semantic Image Interpretation"
collection: projects
permalink: /projects/master_thesis
type: "Master Thesis Project"
venue: "EcoVision Lab,PRS Group,ETH Zürich; Computer Vision Group, TU München"
location: "Zürich, München"
code: https://gitlab.ethz.ch/pchaudha/flood_level_instance
report: https://gitlab.ethz.ch/pchaudha/master-thesis
---

We propose a method to quantify flood water from images gathered from social media. Quantifying flood height by looking just at images is a difficult task. Therefore, in this work we are using common objects of known dimension which are partially submerged in flood water to quantify flood height. There are various factors which makes this task difficult:1. images are cluttered due to presence of different classes;
2. objects of different classes present in various scales depending on the distance at which the image was taken;
3. detection of occluded objects as they are partially submerged in flood water. Also, high intra-class variability of instances of objects like buildings or houses and cars.
We model this problem on two levels. For the first part, we train a network to give per image floodwater-level. For second part, we train a model to give more finer classification. For every instance of an object in an image, the model will predict the class of the object and level of flood. Through this project we also contribute a dataset of flood images gleaned from social media.
