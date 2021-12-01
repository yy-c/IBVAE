# IBVAE
Information bottleneck variational autoencoder

Unsupervised learning is based on latent variables with potential generative factors. This code presents an information bottleneck variational autoencoder algorithm framework to remove redundant noise from high-dimensional data and learn target-related latent variables. First, the Hilbert-Schmidt Independence Criterion is used to define the mutual information between variables. Secondly, an approximate expression of information bottleneck is constructed based on mutual information. Then, a novel loss function is constructed by combining the information bottleneck with a traditional variational autoencoder. Finally, the experimental results on MNIST, CORTEX, CelebA datasets show that the algorithm retains more detailed features of the original data in image generation and performs better in single-cell sequencing than traditional variational autoencoders.


If you have any questions or suggestions, welcome to contact us by email.
E-mail: yang.caoyy@gmail.com
