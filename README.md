# GANs Tutorial

This tutorial works through the necessary pre-requisites to justifying the use of a GAN, and then points to  implementations of GAN using PyTorch & Keras. It is meant to be accessible to those with a basic understanding of machine learning & neural networks.

Working through in this order will help you understand the theory behind GANs, and then how to implement them in practice:

1. [Introduction to GANs](notebooks/intro.ipynb)
1. [Generative Modelling](notebooks/generative_modelling.ipynb)
1. [Divergence vs Metric](notebooks/divergence_vs_metric.ipynb)
1. [Entropy](notebooks/entropy.ipynb)
1. [Cross Entropy](notebooks/cross_entropy.ipynb)
1. [KL Divergence](notebooks/kl_divergence.ipynb)
1. [Jensen-Shannon Divergence](notebooks/js_divergence.ipynb)
1. [Mutual Information](notebooks/mutual_information.ipynb)
1. [Wasserstein Distance](notebooks/wasserstein_distance.ipynb)
1. [MLE](notebooks/mle.ipynb)
1. [Unnormalized Probability](notebooks/unnormalized_probability.ipynb)
1. [Generators](notebooks/generators.ipynb)
1. [Partition Function](notebooks/partition_function.ipynb)
1. [Duality](notebooks/duality.ipynb)
1. [Noise Contrastive Estimation](notebooks/nce.ipynb)
1. [GAN Loss Function](notebooks/gan_loss_function.ipynb)
1. [Fixed Point Theory](notebooks/fixed_point_theory.ipynb)
1. [Nash Equilibrium](notebooks/nash.ipynb)
1. [GAN Existence](notebooks/gan_existence.ipynb)
1. [GAN Exercises](notebooks/gan_exercises.ipynb)
1. Implementations:
    1. Use a LLM to help you write a Linear GAN
        1. Use only `numpy`
        1. Write in a `sklearn` style class interface
        1. Try it out on the `MNIST` dataset or any other dataset
    1. [Keras Generative Tutorials](https://keras.io/examples/generative/)
        1. Five of the tutorials are different varieties of GANs
        1. Can run in Google Colab as good to go notebooks using `keras 3.0`
    1. [Aleksa Gordic's GAN repo](https://github.com/gordicaleksa/pytorch-GANs
        1. uses Pytorch
        1. You'll need to handle conda environment and carefully follow the README
