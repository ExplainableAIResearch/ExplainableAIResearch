---
layout: publication
title: "Interpretable Convolutional Filters with SincNet"
authors: Mirco Ravanelli, Yoshua Bengio
conference: 
year: 2018
additional_links: 
   - {name: "ArXiv", url: "http://arxiv.org/abs/1811.09725v2"}
tags: []
---
Deep learning is currently playing a crucial role toward higher levels of
artificial intelligence. This paradigm allows neural networks to learn complex
and abstract representations, that are progressively obtained by combining
simpler ones. Nevertheless, the internal "black-box" representations
automatically discovered by current neural architectures often suffer from a
lack of interpretability, making of primary interest the study of explainable
machine learning techniques. This paper summarizes our recent efforts to
develop a more interpretable neural model for directly processing speech from
the raw waveform. In particular, we propose SincNet, a novel Convolutional
Neural Network (CNN) that encourages the first layer to discover more
meaningful filters by exploiting parametrized sinc functions. In contrast to
standard CNNs, which learn all the elements of each filter, only low and high
cutoff frequencies of band-pass filters are directly learned from data. This
inductive bias offers a very compact way to derive a customized filter-bank
front-end, that only depends on some parameters with a clear physical meaning.
Our experiments, conducted on both speaker and speech recognition, show that
the proposed architecture converges faster, performs better, and is more
interpretable than standard CNNs.