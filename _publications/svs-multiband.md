---
title: "Multi-band masking for Waveform-based Singing Voice Separation"
collection: publications
excerpt: ''
date: 2022-8-29
status: 'Published'
venue: 'EUSIPCO'
authors: '<strong>Panagiotis Papantonakis</strong>, Christos Garoufis, Petros Maragos'
paperurl: 'https://ieeexplore.ieee.org/document/9909713'
---
Singing Voice Separation (SVS) is the task of isolating the vocal component from a given musical mixture. In recent years there has been an increase in both the quantity and quality of SVS techniques that operate in the waveform domain and have an encoder-separator-decoder structure, where the separator processes a latent representation of the waveform produced by the encoder. In this work, we propose a parallel multi-band modification for this family of architectures, that splits the latent representation provided by the encoder in multiple sub-bands and then processes each band in isolation, using multiple separators, so as to better exploit the internal correlations of each sub-band. We investigate the effect of our proposed modification on Conv-TasNet, a widely used architecture adhering to the encoder-separator-decoder paradigm. The results indicate that the proposed modification improves the overall performance without altering the network size, and offer insights on its scaling capabilities as well as its applicability in other architectures that follow this general paradigm.
