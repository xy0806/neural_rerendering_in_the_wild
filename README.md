# Neural Rerendering in the Wild
Moustafa Meshry<sup>1</sup>, 
[Dan B Goldman](http://www.danbgoldman.com/)<sup>2</sup>, 
[Sameh Khamis](http://www.samehkhamis.com/)<sup>2</sup>, 
[Hugues Hoppe](http://hhoppe.com/)<sup>2</sup>, 
Rohit Pandey<sup>2</sup>, 
[Noah Snavely](http://www.cs.cornell.edu/~snavely/)<sup>2</sup>, 
[Ricardo Martin-Brualla](http://www.ricardomartinbrualla.com/)<sup>2</sup>.

<sup>1</sup>University of Maryland, College Park &nbsp;&nbsp;&nbsp;&nbsp; <sup>2</sup>Google Inc.

To appear at CVPR 2019 (Oral). <br><br>


<figure class="image">
  <!--- <img src="imgs/teaser_with_caption.jpg" width="450px""> --->
  <img align="center" src="https://github.com/MoustafaMeshry/neural_rerendering_in_the_wild/blob/master/imgs/teaser_with_caption.jpg?raw=true" width="500px">
</figure>

<!--- ![Teaser figure](https://github.com/MoustafaMeshry/neural_rerendering_in_the_wild/blob/master/imgs/teaser_with_caption.jpg?raw=true | width=450) --->
                                                                                                                                              
We will provide Tensorflow implementation and pretrained models for our paper soon.

[**Paper**](https://128.84.21.199/pdf/1904.04290.pdf) | [**Video**](https://www.youtube.com/watch?v=E1crWQn_kmY) | [**Code**](https://github.com/MoustafaMeshry/neural_rerendering_in_the_wild) | [**Project page**](https://moustafameshry.github.io/neural_rerendering_in_the_wild/)

### Abstract

We explore total scene capture — recording, modeling, and rerendering a scene under varying appearance such as season and time of day.
Starting from internet photos of a tourist landmark, we apply traditional 3D reconstruction to register the photos and approximate the scene as a point cloud.
For each photo, we render the scene points into a deep framebuffer,
and train a neural network to learn the mapping of these initial renderings to the actual photos.
This rerendering network also takes as input a latent appearance vector and a semantic mask indicating the location of transient objects like pedestrians.
The model is evaluated on several datasets of publicly available images spanning a broad range of illumination conditions.
We create short videos demonstrating realistic manipulation of the image viewpoint, appearance, and semantic labeling.
We also compare results with prior work on scene reconstruction from internet photos.

### Video
[![cvpr_video](https://img.youtube.com/vi/E1crWQn_kmY/0.jpg)](https://www.youtube.com/watch?v=E1crWQn_kmY)

<!---
### Paper
--->

<!---
### Results
<figure class="image">
  <img src="imgs/teaser/teaser_part1.jpg" width="450px">
  <figcaption>(a) Input deep buffer</figcaption>
  <img src="imgs/teaser/teaser_part2.jpg" width="450px">
  <figcaption>(b) Output rerenderings</figcaption>
</figure>
<figure class="image">
  <img src="imgs/teaser_with_caption.jpg" width="450px"">
</figure>
--->
                                                        
### Appearance variation
<figure class="image">
  <img src="imgs/app_variatoin.jpg" width="900px">
</figure>
<!--- [![app_variation] (https://github.com/MoustafaMeshry/neural_rerendering_in_the_wild/blob/master/imgs/app_variatoin.jpg?raw=true | width=900)] --->

### Appearance interpolation
<figure class="image">
  <img src="imgs/app_interpolation.jpg" width="900px">
</figure>
<!--- [![app_interpolation] (https://github.com/MoustafaMeshry/neural_rerendering_in_the_wild/blob/master/imgs/app_interpolation.jpg?raw=true | width=900)] --->

### Acknowledgements
We thank Gregory Blascovich for his help in conducting the user study, and Johannes Schönberger and True Price for their help generating datasets.
