In this repository, we study unsupervised learning (clustering) and classification problem using the [Flower data set](https://www.robots.ox.ac.uk/~vgg/data/flowers/). In this repo, a small subset of the original data is used.

There are three implementations:

## Clustering based approach
  * [Principle Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis) (PCA)
  * [t-Distributed Stochastic Neighbor Embedding](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding) (t-SNE)
  * [Uniform Manifold Approximation and Projection](https://arxiv.org/abs/1802.03426) (UMAP)
  
Additionl Materials:

- [tSNE vs. UMAP: Global Structure](https://towardsdatascience.com/tsne-vs-umap-global-structure-4d8045acba17)
  
## Classification implementation using PyTorch
By following [a PyTorch tutorial](https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html), the VGG16 network is fine-tuned using PyTorch and all necessary steps are implemented from skretch.

## Classification implementation using Fastai
The [Fastai library](https://docs.fast.ai/) is used to fine the VGG16 network. Fatsai is a high-level API for PyTorch. It has some nice features included such as a fancy image augumentation. 


  

