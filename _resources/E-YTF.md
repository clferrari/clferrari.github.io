---
title: "Extended YouTube Faces Dataset"
collection: resources
permalink: /resources/E-YTF
excerpt: 'An extension of the YouTube Faces (YTF) dataset comprising still images and video frames tailored for the task of face recognition'
date: 2018-08-01
venue: 'International Conference on Pattern Recognition (ICPR)'
---
![Paper image!](/images/e-ytf.png)

—In this paper, we propose an extension of the famous
YouTube Faces (YTF) dataset. In the YTF dataset, the goal was
to state whether two videos contained the same subject or not
(video-based face verification). We enrich YTF with still images
and an identification protocol. In the classic face identification,
given a probe image (or video), the correct identity has to
be retrieved among the gallery ones; the main peculiarity of
such protocol is that each probe identity has a correspondent
in the gallery (closed-set). To resemble a realistic and practical
scenario, we devised a protocol in which probe identities are not
guaranteed to be in the gallery (open-set). Compared to a closedset identification, the latter is definitely more challenging in as
much as the system needs firstly to reject impostors (i.e., probe
identities missing from the gallery), and subsequently, if the probe
is accepted as genuine, retrieve the correct identity. In our case,
the probe set is composed of full-length videos from the original
dataset, while the gallery is composed of templates, i.e., sets of
still images. To collect the images, an automatic application was
developed. The main motivations behind this work can be found
in both the lack of open-set identification protocols defined in
the literature and the undeniable complexity of such. We also
argued that extending an existing and widely used dataset could
make its distribution easier and that data heterogeneity would
make the problem even more challenging and realistic. We named
the dataset Extended YTF (E-YTF). [Download paper here](https://www.micc.unifi.it/wp-content/uploads/2019/01/ICPR_2018.pdf)

Dataset is available at this [link](https://www.micc.unifi.it/resources/datasets/e-ytf/)!

If you find our work useful, please cite us: 
 
>@inproceedings{ferrari2018extended,  
>  title={Extended youtube faces: a dataset for heterogeneous open-set face identification},  
>  author={Ferrari, Claudio and Berretti, Stefano and Del Bimbo, Alberrto},  
>  booktitle={2018 24th International Conference on Pattern Recognition (ICPR)},  
>  pages={3408--3413},  
>  year={2018},  
>  organization={IEEE}}  









