---
title: "Learning Streamed Attention Network from Descriptor Images for Cross-Resolution 3D Face Recognition"
collection: publications
permalink: /publication/TOMM3D
excerpt: 'In this article, we propose a hybrid framework for cross-resolution 3D face recognition which utilizes a Streamed Attention Network (SAN) that combines handcrafted features with Convolutional Neural Networks (CNNs).'
date: 2022-08-01
venue: 'ACM Transactions on Multimedia Computing Communications and Applications (TOMM)'
---

In this paper, we propose a hybrid framework for cross-resolution 3D face recognition which utilizes a Streamed Attention
Network (SAN) that combines hand-crafted features with Convolutional Neural Networks (CNNs). It consists of two main
stages: irst, we process the depth images to extract low-level surface descriptors and derive the corresponding Descriptor
Images (DIs), represented as 4-channel images. To build the DIs, we propose a variation of the 3D Local Binary Pattern
(3DLBP) operator that encodes depth diferences using a sigmoid function. Then, we design a CNN that learns from these DIs.
The peculiarity of our solution consists in processing each channel of the input image separately, and fusing the contribution
of each channel by means of both self- and cross-attention mechanisms. This strategy showed two main advantages over the
direct application of Deep-CNN to depth images of the face; on the one hand, the DIs can reduce the diversity between highand low-resolution data by encoding surface properties that are robust to resolution diferences. On the other, it allows a better exploitation of the richer information provided by low-level features, resulting in improved recognition. We evaluated
the proposed architecture in a challenging cross-dataset, cross-resolution scenario. To this aim, we irst train the network
on scanner-resolution 3D data. Next, we utilize the pre-trained network as feature extractor on low-resolution data, where
the output of the last fully connected layer is used as face descriptor. Other than standard benchmarks, we also perform
experiments on a newly collected dataset of paired high- and low-resolution 3D faces. We use the high-resolution data as
gallery, while low-resolution faces are used as probe, allowing us to assess the real gap existing between these two types of
data. Extensive experiments on low-resolution 3D face benchmarks show promising results with respect to state-of-the-art
methods. [Download paper here](https://air.unipr.it/bitstream/11381/2920469/1/3527158.pdf)

Code is available at this [GitHub](https://github.com/jbcnrlz/san) link!

If you find our work useful, please cite us: 
 
>@article{neto2023learning,  
>  title={Learning Streamed Attention Network from Descriptor Images for Cross-Resolution 3D Face Recognition},  
>  author={Neto, Jo{\~a}o Baptista Cardia and Ferrari, Claudio and Marana, Aparecido Nilceu and Berretti, Stefano and Del Bimbo, Alberto},  
>  journal={ACM Transactions on Multimedia Computing, Communications and Applications},  
>  volume={19},  
>  number={1s},  
>  pages={1--20},  
>  year={2023},  
>  publisher={ACM New York, NY}}  













