---
title: "Content-Aware Texturing for Gaussian Splatting"
collection: publications
excerpt: ''
date: 2025-5-23
status: 'Published'
venue: 'EGSR'
authors: '<strong>Panagiotis Papantonakis</strong>, Georgios Kopanas, Frédo Durand, George Drettakis'
paperurl: 'https://hal.science/hal-05201179v1'
projectpage: 'https://repo-sam.inria.fr/nerphys/gs-texturing'
code: 'https://github.com/graphdeco-inria/gs-texturing'
header:
    teaser: gs-texturing_teaser.png
---
Gaussian Splatting has become the method of choice for 3D reconstruction and real-time rendering of captured real scenes. However, fine appearance details need to be represented as a large number of small Gaussian primitives, which can be wasteful when geometry and appearance exhibit different frequency characteristics. Inspired by the long tradition of texture mapping, we propose to use texture to represent detailed appearance where possible. Our main focus is to incorporate per-primitive texture maps that adapt to the scene in a principled manner during Gaussian Splatting optimization. We do this by proposing a new appearance representation for 2D Gaussian primitives with textures where the size of a texel is bounded by the image sampling frequency and adapted to the content of the input images. We achieve this by adaptively upscaling or downscaling the texture resolution during optimization. In addition, our approach enables control of the number of primitives during optimization based on texture resolution. We show that our approach performs favorably in image quality and total number of parameters used compared to alternative solutions for textured Gaussian primitives.