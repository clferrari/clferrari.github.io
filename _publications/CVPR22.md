---
title: "Sparse to dense dynamic 3d facial expression generation"
collection: publications
permalink: /publication/CVPR22
excerpt: 'In this paper, we propose a solution to the task of generating dynamic 3D facial expressions from a neutral 3D face and an expression label.'
date: 2022-08-01
venue: 'IEEE/CVF International Conference on Computer Vision and Pattern Recognition (CVPR)'
---
![Paper image!](/images/cvpr22.png)

In this paper, we propose a solution to the task of generating dynamic 3D facial expressions from a neutral 3D face and an expression label. This involves solving two sub-problems:(i) modeling the temporal dynamics of expressions, and (ii) deforming the neutral mesh to obtain the expressive counterpart. We represent the temporal evolution of expressions using the motion of a sparse set of 3D landmarks that we learn to generate by training a manifold-valued GAN (Motion3DGAN). To better encode the expression-induced deformation and disentangle it from the identity information, the generated motion is represented as per-frame displacement from a neutral configuration. To generate the expressive meshes, we train a Sparse2Dense mesh Decoder (S2D-Dec) that maps the landmark displacements to a dense, per-vertex displacement. This allows us to learn how the motion of a sparse set of landmarks influences the deformation of the overall face surface, independently from the identity. Experimental results on the CoMA and D3DFACS datasets show that our solution brings significant improvements with respect to previous solutions in terms of both dynamic expression generation and mesh reconstruction, while retaining good generalization to unseen data.  [Download paper here](https://openaccess.thecvf.com/content/CVPR2022/papers/Otberdout_Sparse_to_Dense_Dynamic_3D_Facial_Expression_Generation_CVPR_2022_paper.pdf)

Code is available at this [GitHub](https://github.com/CRISTAL-3DSAM/Sparse2Dense) link!

If you find our work useful, please cite us: 
 
>@inproceedings{otberdout2022sparse,  
>  title={Sparse to dense dynamic 3d facial expression generation},  
>  author={Otberdout, Naima and Ferrari, Claudio and Daoudi, Mohamed and Berretti, Stefano and Del Bimbo, Alberto},  
>  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},  
>  pages={20385--20394},  
>  year={2022}}  











