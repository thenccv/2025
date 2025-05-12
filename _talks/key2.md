---
name: 3D Reconstruction with Gaussian Splatting
speakers:
  - Torsten Sattler
categories:
  - Keynote
hide: False
---

Accurate 3D reconstruction is a core computer vision problem with many applications, including autonomous robots such as self-driving cars, cultural heritage documentation, and content creation for the entertainment industry (movies, games, etc.). Traditionally, 3D reconstructions have been based on 3D meshes and point clouds. Recently, learning-based approaches, such as neural radiance fields (NeRFs) and most recently 3D Gaussian Splatting (3DGS), have become popular. These representations are learned from images with known intrinsics and extrinsics and generate (close-to) photorealistic representations of scenes and objects. Compared to NeRFs, which can be slow to train and slow to render, 3DGS offers both faster training and test times. This talk first briefly reviews the original 3DGS formulation before identifying shortcomings and explaining how to resolve them. In particular, we will discuss (i) how to handle artifacts in the reconstruction caused by a limited set of training viewpoints, (ii) how to extend the original formulation for handling images taken under different conditions (day, night, etc.), and (iii) how to extract accurate 3D meshes from 3DGS representations by defining a field on top of the 3D Gaussians used to represent the scene. In addition, we will briefly mention ongoing efforts to ensure that benchmark results are comparable and that comparisons are fair.