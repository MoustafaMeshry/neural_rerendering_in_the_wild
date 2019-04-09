# Neural Rerendering in the Wild
Moustafa Meshry<sup>1</sup>, Dan B Goldman<sup>2</sup>, Sameh Khamis<sup>2</sup>, Hugue Hoppe<sup>2</sup>, Rohit Pandey<sup>2</sup>, Noah Snavely<sup>2</sup>, Ricardo Martin-Brualla<sup>2</sup>.

<sup>1</sup>University of Maryland, College Park &nbsp;&nbsp;&nbsp;&nbsp; <sup>2</sup>Google Inc.

To appear at CVPR 2019 (Oral). <br><br>


We will provide Tensorflow implementation and pretrained models for our paper soon.

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
