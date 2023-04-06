---
title: "A sparse and locally coherent morphable face model for dense semantic correspondence across heterogeneous 3D faces"
collection: publications
permalink: /publication/TPAMI21
excerpt: 'In this work, we propose a novel sparse 3D Morphable Model construction pipeline, together with a landmark-free dense 3D face registration techinque.'
date: 2021-08-01
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)'
---
![Paper image!](/images/TPAMI.png)

—The 3D Morphable Model (3DMM) is a powerful statistical tool for representing 3D face shapes. To build a 3DMM, a training
set of face scans in full point-to-point correspondence is required, and its modeling capabilities directly depend on the variability
contained in the training data. Thus, to increase the descriptive power of the 3DMM, establishing a dense correspondence across
heterogeneous scans with sufficient diversity in terms of identities, ethnicities, or expressions becomes essential. In this manuscript,
we present a fully automatic approach that leverages a 3DMM to transfer its dense semantic annotation across raw 3D faces,
establishing a dense correspondence between them. We propose a novel formulation to learn a set of sparse deformation components
with local support on the face that, together with an original non-rigid deformation algorithm, allow the 3DMM to precisely fit unseen
faces and transfer its semantic annotation. We extensively experimented our approach, showing it can effectively generalize to highly
diverse samples and accurately establish a dense correspondence even in presence of complex facial expressions. The accuracy of
the dense registration is demonstrated by building a heterogeneous, large-scale 3DMM from more than 9,000 fully registered scans
obtained by joining three large datasets together  [Download paper here](https://ieeexplore.ieee.org/abstract/document/9462361)

Code is available at this [GitHub](https://github.com/clferrari/SLC-3DMM) link!

If you find our work useful, please cite us: 
 
>@article{ferrari2021sparse,  
>  title={A sparse and locally coherent morphable face model for dense semantic correspondence across heterogeneous 3D faces},  
>  author={Ferrari, Claudio and Berretti, Stefano and Pala, Pietro and Del Bimbo, Alberto},  
>  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},  
>  volume={44},  
>  number={10},  
>  pages={6667--6682},  
>  year={2021},  
>  publisher={IEEE}}   









