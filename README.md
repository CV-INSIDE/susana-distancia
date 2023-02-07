# *SuSana Distancia is all you need:* Enforcing class separability in metric learning via two novel distance-based loss functions for few-shot image classification


## Abstract

Few-shot learning is a challenging area of research that aims to learn new concepts with only a few labeled samples of data. Recent works based on metric-learning approaches leverage the meta-learning  approach,  which is encompassed by episodic tasks that make use a support (training) and query set (test) with the objective of learning a similarity comparison metric between those sets. Due to the lack of data, the learning process of the embedding network becomes an important part of the few-shot task.
Previous works have addressed this problem using metric learning approaches, but the properties of the underlying latent space and the separability of the difference classes on it was not entirely enforced.
In this work, we propose two different loss functions which consider the importance of the embedding vectors by looking at the intra-class and inter-class distance between the few data. The first loss function is the Proto-Triplet Loss, which is based on the original triplet loss with the modifications needed to better work on few-shot scenarios. The second loss function is based on an inter and intra class nearest neighbors score, which help us to assess the quality of embeddings obtained from the trained network. Our results, obtained from a extensive experimental setup show a significant improvement in accuracy in the miniImagenNet benchmark compared to other metric-based few-shot learning methods by a margin of $2\%$, demonstrating the capability of these loss functions to allow the network to generalize better to previously unseen classes. In our experiments, we demonstrate competitive generalization capabilities to other domains, such as the Caltech CUB, DGos and Cars datasets compared with the state of the art.


[[Paper]]() 




---

## Contents

 
 
 
## Summary 


 
## Organization

No additional content directories are declared. 


## Contributors

Code for algorithms, applications and tools contributed by:

[Gilberto Ochoa](https://scholar.google.com/citations?user=DDtiliwAAAAJ&hl=en&authuser=1)

Please email us your comments, criticism, and questions at [`gilberto.ochoa@tec.mx`](mailto:gilberto.ochoa@tec.mx?subject=[GitHub]%20ks-baseline%20repository)


## Reference

If you use functions from this script in your work, please use the BibTex entry below for citation.

[[Paper]]()

```

```

