layout: page
title: main
permalink: /main/
---

# Musika! <br/> Fast Infinite Waveform Music Generation

<!-- ![Banner](logo.png) -->
<img src="logo.png">

{% include video source="youtube" id="QBl8y2Z_i7Y" %}

**Abstract**  
Fast and user-controllable music generation could enable novel ways of composing music. However, state-of-the-art music generation systems require large amounts of data and computational resources for training, and are slow at inference. This makes them impractical for real-time interactive use. In this work, we introduce Musika, a music generation system that can be trained on hundreds of hours of music using a single consumer GPU, and that allows for much faster than real-time generation of music of arbitrary length on a consumer CPU. We achieve this by first learning a compact invertible representation of spectrogram magnitudes and phases with adversarial autoencoders, then training a Generative Adversarial Network (GAN) on this representation for a particular music domain. A latent coordinate system enables generating arbitrarily long sequences of excerpts in parallel, while a global context vector allows the music to remain stylistically coherent through time. We perform quantitative evaluations to assess the quality of the generated samples and showcase options for user control in piano and techno music generation. We release the source code and pretrained autoencoder weights, such that a GAN can be trained on a new music domain with a single GPU in a matter of hours.
