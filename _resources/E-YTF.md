---
title: "Deep 3D Morphable Model Refinement via Progressive Growing of Conditional Generative Adversarial Networks"
collection: resources
permalink: /resources/E-YTF
excerpt: 'An extension of the YouTube Faces (YTF) dataset comprising still images and video frames tailored for the task of face recognition'
date: 2018-08-01
venue: 'International Conference on Pattern Recognition (ICPR)'
---
![Paper image!](/images/e-ytf.png)

In this work, we propose an approach based on a Conditional Generative Adversarial Network (CGAN) for refining the coarse reconstruction provided by a 3DMM. The latter is represented as a three channels image, where the pixel intensities represent the depth, curvature and elevation values of the 3D vertices. The architecture is an encoder–decoder, which is trained progressively, starting from the lower-resolution layers; this technique allows a more stable training, which leads to the generation of high quality outputs even when high-resolution images are fed during the training. Experimental results show that our method is able to produce reconstructions with fine-grained realistic details and lower reconstruction errors with respect to the 3DMM.  [Download paper here](https://www.micc.unifi.it/wp-content/uploads/2019/01/ICPR_2018.pdf)

Dataset is available at this [link](https://www.micc.unifi.it/resources/datasets/e-ytf/)!

If you find our work useful, please cite us: 
 
>@inproceedings{ferrari2018extended,  
>  title={Extended youtube faces: a dataset for heterogeneous open-set face identification},  
>  author={Ferrari, Claudio and Berretti, Stefano and Del Bimbo, Alberrto},  
>  booktitle={2018 24th International Conference on Pattern Recognition (ICPR)},  
>  pages={3408--3413},  
>  year={2018},  
>  organization={IEEE}}  









