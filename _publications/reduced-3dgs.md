---
title: "Reducing the Memory Footprint of 3D Gaussian Splatting"
collection: publications
excerpt: ''
date: 2023-4-28
status: 'Published'
venue: 'I3D'
authors: '<strong>Panagiotis Papantonakis</strong>, Georgios Kopanas, Bernhard Kerbl, Alexandre Lanvin, George Drettakis'
paperurl: 'https://hal.science/hal-04550892/'
projectpage: 'https://repo-sam.inria.fr/fungraph/reduced_3dgs'
code: 'https://github.com/graphdeco-inria/reduced-3dgs'
header:
    teaser: reduced-3dgs.jpg
---
3D Gaussian splatting provides excellent visual quality for novel view synthesis, with fast training and real-time rendering; unfortunately, the memory requirements of this method for storing and transmission are unreasonably high. We first analyze the reasons for this, identifying three main areas where storage can be reduced: the number of 3D Gaussian primitives used to represent a scene, the number of coefficients for the spherical harmonics used to represent directional radiance, and the precision required to store Gaussian primitive attributes. We present a solution to each of these issues. First, we propose an efficient, resolution-aware primitive pruning approach, reducing the primitive count by half. Second, we introduce an adaptive adjustment method to choose the number of coefficients used to represent directional radiance for each Gaussian primitive, and finally a codebook-based quantization method, together with a half-float representation for further memory reduction. Taken together, these three components result in a ×27 reduction in overall size on disk on the standard datasets we tested, along with a ×1.7 speedup in rendering speed. We demonstrate our method on standard datasets and show how our solution results in significantly reduced download times when using the method on a mobile device.