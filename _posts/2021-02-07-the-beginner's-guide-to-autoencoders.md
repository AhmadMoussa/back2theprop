---
title: Origins of the Autoencoder
categories:
- Unsupervised Learning
excerpt: |
  Autoencoders are your bread and butter when it comes to dimensionality reduction and feature extraction. This blog post explains in detail their inner workings.
feature_text: |
  ## The Autoencoder
  The autoencoder is an unsupervised learning model that utilizes an encoder and a decoder to learn a latent representation of data.
feature_image: "https://picsum.photos/2560/600?image=733"
image: "https://picsum.photos/2560/600?image=733"
---

I love the autoencoder, because it's such a versatile model to have in your machine learning toolkit. While the regular autoencoder is a relatively simple model, it teaches you some of the fundamental concepts of the last decade in deep learning, which gives you a foot in the door for more advanced models such as Latent variable models and generative adversarial networks, and hence making them more accessible.

### Origins of the Autoencoder
One of the fascinating things about the autoencoder is that there is no clear consensus about it's origins. A cursory google search does not immediately reveal to us a clear pointer towards source. However, we are met with a Cross Validated Stack Exchange question that is also inquiring about exactly the same issue. The top answer points towards an article by Schmidhuber "Deep learning in neural networks: an overview" which states that 'Perhaps the first work to study potential benefits of UL-based pre-training was published in 1987. It proposed unsupervised AE hierarchies (Ballard, 1987), closely related to certain post-2000 feedforward Deep Learners based on UL'. The study that he is citing here is called 'Modular learning in neural networks' and discusses pre-training for the first time.

The second, unapproved, answer to the same question points to an earlier paper released in 1986 named 'Learning internal representations by error propagation' by Rumelhart, Hinton and Williams. Which is in concordance with more recent works that also cite this work as being the first work to introduce autoencoders.

### Learning internal representations by Error Propagation

{% include figure.html image="https://i.imgur.com/H2jZ5xJ.png" alt="Image with just alt text" %}

It is worth it to spend some reading the paper as it explains with an incredible clarity the concept of a neural network with a hidden representation.

### Towards modern applications of Autoencoders
A noteworthy article is 'Reducing the Dimensionality of Data with Neural Networks' by Hinton, which is maybe the first study to apply auto-encoders in the context of images.

