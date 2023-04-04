---
title: "Effective 3D based Frontalization for Unconstrained Face Recognition"
collection: publications
permalink: /publication/ICPR16
excerpt: 'In this paper, we propose a new and effective frontalization algorithm based on a 3D Morphable Face Model (3DMM) for frontal rendering of unconstrained face images, to be used for face recognition.'
date: 2016-12-04
venue: 'International Conference on Pattern Recognition (ICPR)'
paperurl: 'http://clferrari.github.io/files/ICPR16.pdf'
---
In this paper, we propose a new and effective frontalization algorithm for frontal rendering of unconstrained face images, and experiment it for face recognition. Initially, a 3DMM is fit to the image, and an interpolating function maps each pixel inside the face region on the image to the 3D model’s. Thus, we can render a frontal view without introducing artifacts in the final image thanks to the exact correspondence between each pixel and the 3D coordinate of the model. The 3D model is then back projected onto the frontalized image allowing us to localize image patches where to extract the feature descriptors, and thus enhancing the alignment between the same descriptor over different images.

![Paper image!](/images/icpr.png)

[Download paper here](http://academicpages.github.io/files/paper1.pdf)

A pre-processed version of the Labeled Faces in The Wild ([LFW](http://vis-www.cs.umass.edu/lfw/)) dataset can be found [here](https://www.micc.unifi.it/resources/datasets/frontalized-faces-in-the-wild/).

Citation: 
 
>@inproceedings{ferrari2016effective,  
>  title={Effective 3D based frontalization for unconstrained face recognition},  
>  author={Ferrari, Claudio and Lisanti, Giuseppe and Berretti, Stefano and Del Bimbo, Alberto},  
>  booktitle={2016 23rd International Conference on Pattern Recognition (ICPR)},  
>  pages={1047--1052},  
>  year={2016},  
>  organization={IEEE}}  

