---
title: "(Compress and Restore): a Robust Defense Against Adversarial Attacks on Image Classification"
collection: publications
permalink: /publication/TOMMnoobs
excerpt: 'In this paper, we propose a conceptually simple yet robust solution to tackle adversarial attacks on image classification. Our
defense works by first applying a JPEG compression with a random quality factor; compression artifacts are subsequently
removed by means of a generative model (AR-GAN).'
date: 2022-08-01
venue: 'ACM Transactions on Multimedia Computing Communications and Applications (TOMM)'
---

![Paper image!](/images/tomm_noobs.png)


Modern image classification approaches often rely on deep neural networks, which have shown pronounced weakness to
adversarial examples: images corrupted with specifically designed yet imperceptible noise that causes the network to misclassify.
In this paper, we propose a conceptually simple yet robust solution to tackle adversarial attacks on image classification. Our
defense works by first applying a JPEG compression with a random quality factor; compression artifacts are subsequently
removed by means of a generative model (AR-GAN). The process can be iterated ensuring the image is not degraded and hence
the classification not compromised. We train different AR-GANs for different compression factors, so that we can change its
parameters dynamically at each iteration depending on the current compression, making the gradient approximation difficult.
We experiment our defense against three white-box and two black-box attacks, with a particular focus on the state-of-the-art
BPDA attack. Our method does not require any adversarial training, and is independent of both the classifier and the attack.
Experiments demonstrate that dynamically changing the AR-GAN parameters is of fundamental importance to obtain significant
robustness. [Download paper here](https://flore.unifi.it/bitstream/2158/1271425/4/3524619.pdf)

If you find our work useful, please cite us: 
 
>@article{ferrari2023compress,  
>  title={(Compress and Restore) N: A Robust Defense Against Adversarial Attacks on Image Classification},  
>  author={Ferrari, Claudio and Becattini, Federico and Galteri, Leonardo and Bimbo, Alberto Del},  
>  journal={ACM Transactions on Multimedia Computing, Communications and Applications},  
>  volume={19},  
>  number={1s},  
>  pages={1--16},  
>  year={2023},  
>  publisher={ACM New York, NY}}  















