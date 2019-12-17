# Table of Contents
- [Concept](#1-concept)
- [Scene](#2-scene)
- [mage Features](#3-image-features)
- [Code Features](#4-code-features)
- [Acceleration](#5-acceleration)
- [Build](#6-build)
- [Acknowledgment](#7-acknowledgment)
- [Team](#8-team)
- [Comments](#9-comments)

# 1. Concept
### Habib's Reception.

One of our group member had this idea to render the reception of Habib. The philosophy behind this scene is 
We thought that it would be pretty cool to have a customizable chess board as our scene. One of our team members spent a good amount of time this semester building a chess AI for another class, and so the subject matter was on our mind, and we figured that it would be neat if we could render pleasing-looking scenes representing arbitrary chess states. Once we had a basic rendering of our board, we played around with adding things like reflectance on the tiles. We used chess pieces with a lot of polygons to show off our ray tracer using a complex scene.

# 2. Scene
We built this scene using triangles and imported models as smooth triangles for the chess pieces. In this scene we use perspecitve viewing and include several point light sources with ambient lighting to render the scene. We also use Jitter-Gaussian anti-aliasing to smooth out the jaggies with 9 rays per pixel. Overall, there are 650,000+ polygons captured in our scene which took around 20 seconds to render using a KD tree and multithreading on 8 cores.

# 3. Image Features
 highlight interesting parts or features of your render. Additional images may be
 included for this purpose.

# 4. Code Features 
list all the features you have implemented in your ray tracer. This includes changes
made for Homework 5 and for this project.

# 5. Acceleration 
include a table comparing rendering times of your ray tracer with and without an
acceleration structure. Supporting renderings must be included.

# 6. Build 
for every image included on the page, a link to the corresponding implementation of World::build,

# 7. Acknowledgment 
acknowledge all third party sources of used assets or resources, once where
they are used, e.g. in the caption of a rendered image, and again in an Acknowledgment
section toward the bottom of the page.
We have used the following third party resources for our project.
- Kevin Suffern's Ray Tracing from the Ground Up

- Nicholas Sharp's hapPLY for parsing PLY files

- Team-Raytracer github repository. 

# 8. Team 
 ![Syed M, Hasan](images/hasan.png) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
 ![Emad Bin Abid](images/emad.png) &nbsp; &nbsp; &nbsp; &nbsp; 
 ![Saman Ghaziani](images/saman.jpeg)
 
**Syed M. Hasan**  &nbsp; &nbsp; &nbsp; &nbsp; **Emad Bin Abid** &nbsp; &nbsp; &nbsp; &nbsp; **Saman Ghaziani**

# 9. Comments 
include any other comments desired by the team.

