# Neural Rerendering in the Wild

We will provide Tensorflow implementation and pretrained models for our paper soon.

Neural Rerendering in the Wild.<br>
Moustafa Meshry, Dan B Goldman, Sameh Khamis, Hugue Hoppe, Rohit Pandey, Noah Snavely, Ricardo Martin-Brualla.<br>
In CVPR 2019 (Oral).

### Video
[![cvpr_video](https://img.youtube.com/vi/Mq9OCKpFaUs/0.jpg)](https://www.youtube.com/watch?v=Mq9OCKpFaUs)

### Abstract

We explore total scene capture — recording, modeling, and rerendering a scene under varying appearance such as season and time of day.
Starting from internet photos of a tourist landmark, we apply traditional 3D reconstruction to register the photos and approximate the scene as a point cloud.
For each photo, we render the scene points into a deep framebuffer,
and train a neural network to learn the mapping of these initial renderings to the actual photos.
This rerendering network also takes as input a latent appearance vector and a semantic mask indicating the location of transient objects like pedestrians.
The model is evaluated on several datasets of publicly available images spanning a broad range of illumination conditions.
We create short videos demonstrating realistic manipulation of the image viewpoint, appearance, and semantic labeling.
We also compare results with prior work on scene reconstruction from internet photos.

### Paper

### Results
