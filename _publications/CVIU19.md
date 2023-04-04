---
title: "Deep 3D Morphable Model Refinement via Progressive Growing of Conditional Generative Adversarial Networks"
collection: publications
permalink: /publication/CVIU19
excerpt: 'In this work, we propose an approach based on a Conditional Generative Adversarial Network (CGAN) for refining the coarse face reconstruction as obtained with standard 3DMM fitting techniques.'
date: 2019-08-01
venue: 'Computer Vision and Image Understanding (CVIU)'
---
![Paper image!](/images/cviu.png)

In this work, we propose an approach based on a Conditional Generative Adversarial Network (CGAN) for refining the coarse reconstruction provided by a 3DMM. The latter is represented as a three channels image, where the pixel intensities represent the depth, curvature and elevation values of the 3D vertices. The architecture is an encoder–decoder, which is trained progressively, starting from the lower-resolution layers; this technique allows a more stable training, which leads to the generation of high quality outputs even when high-resolution images are fed during the training. Experimental results show that our method is able to produce reconstructions with fine-grained realistic details and lower reconstruction errors with respect to the 3DMM.  [Download paper here](https://www.sciencedirect.com/science/article/pii/S1077314219300773)

Code is available at this [GitHub](https://github.com/clferrari/deep-3dmm-refinement) link!

If you find our work useful, please cite us: 
 
>@article{galteri2019deep,  
>  title={Deep 3D morphable model refinement via progressive growing of conditional Generative Adversarial Networks},  
>  author={Galteri, Leonardo and Ferrari, Claudio and Lisanti, Giuseppe and Berretti, Stefano and Del Bimbo, Alberto},  
>  journal={Computer Vision and Image Understanding},  
>  volume={185},  
>  pages={31--42},  
>  year={2019},  
>  publisher={Elsevier}}  







