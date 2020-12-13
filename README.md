## Custom Light Probes [Unity, C#]
----------------------------------------------------------------------------------------
#### Dec 2020

#### Light Probe custom implementation using Spherical Harmonics for fast realtime GI results.
## Without Light Probe GI
![](https://raw.githubusercontent.com/vincent-breysse/light-probes/master/Screen/1-0.png)
## With Light Probe GI
![](https://raw.githubusercontent.com/vincent-breysse/light-probes/master/Screen/1-1.png)
## SH coefficients interpolation
![](https://via.placeholder.com/15/FFFF00/000000?text=+) **Light probes**  
![](https://raw.githubusercontent.com/vincent-breysse/light-probes/master/Screen/3.png)
## Probe Environment map (left) and Irradiance map approximation (right) using order 2 Spherical Harmonics (9 coefficients per color channel)
![](https://raw.githubusercontent.com/vincent-breysse/light-probes/master/Screen/4.png)

#### More details : https://github.com/vincent-breysse/light-probes

## Culling system [Unity, C#, DOTS]
----------------------------------------------------------------------------------------
#### Nov 2020

#### Unity ECS implementation of a typical Culling system supporting Frustrum Culling and Occlusion Culling
## Viewer perspective
![](https://raw.githubusercontent.com/vincent-breysse/culling/main/Screen/0.png)
![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) **Not culled**  
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) **Culled by Occluders**  
![#888888](https://via.placeholder.com/15/888888/000000?text=+) **Out of Frustrum**  
## Debug view
![](https://raw.githubusercontent.com/vincent-breysse/culling/main/Screen/2.png)
![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) **Not culled**  
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) **Culled by Occluders**  
![#888888](https://via.placeholder.com/15/888888/000000?text=+) **Out of Frustrum**  

## Octree first layer
![](https://raw.githubusercontent.com/vincent-breysse/culling/main/Screen/3.png)

#### More details : https://github.com/vincent-breysse/culling

# WhichCraft [Unity, C#]
-------------------------------------------------------
#### Oct 2019 – May 2020

#### Top down 3D action game we did during our 3rd year of studies. For the most part, the project has been done remotely during the Covid-19 pandemic.

### Trailer
[![Trailer](https://img.youtube.com/vi/FjbEneLxB-M/0.jpg)](https://www.youtube.com/watch?v=FjbEneLxB-M)

#### More details : https://github.com/vincent-breysse/whichcraft

# Path tracer [C++, SFML]
-------------------------------------------------------
#### Mar 2020

#### Simple multithreaded path tracer using Monte Carlo integration.
![](https://raw.githubusercontent.com/vincent-breysse/path_tracer/master/screen/0.png)

#### More details : https://github.com/vincent-breysse/path_tracer

# CJOpenGL [C++, OpenGL]
-------------------------------------------------------
#### Oct 2019 – Mar 2020

#### Generalist game engine including support for graphics and physics with a convenient Unity-like OOP interface.  

### Simple Albedo/Specular/Normal map based rendering
![](https://raw.githubusercontent.com/vincent-breysse/cj_opengl/master/screens/3.png)
### Outdoor scene using the above plus a Skybox, HDR, Bloom and SSAO
![](https://raw.githubusercontent.com/vincent-breysse/cj_opengl/master/screens/1.png)
### Indoor scene without SSAO
![](https://raw.githubusercontent.com/vincent-breysse/cj_opengl/master/screens/4.png)
### Indoor scene with SSAO
![](https://raw.githubusercontent.com/vincent-breysse/cj_opengl/master/screens/5.png)
### Glass rendering based on an Environment map
![](https://raw.githubusercontent.com/vincent-breysse/cj_opengl/master/screens/2.png)

#### More details : https://github.com/vincent-breysse/cj_opengl

## Trym [C++, Vulkan]
-------------------------------------------------------
#### Oct 2019 – Feb 2020

#### Graphics engine with focus on low-level graphics, performances and software architecture. The engine uses Tryl (which is one of my projects) as its core library : https://github.com/vincent-breysse/tryl

### Entity rendering using Phong lighting, Texturing and Shadowing
![Simple scene screen](https://raw.githubusercontent.com/vincent-breysse/trym/master/screens/0.png)

### Same as above with a Black and White Post Processing effect
![Simple scene screen](https://raw.githubusercontent.com/vincent-breysse/trym/master/screens/1.png)

### Slide example (I had to give a talk in class)
![0](https://raw.githubusercontent.com/vincent-breysse/trym/master/screens/slides/4.png)

#### More details : https://github.com/vincent-breysse/trym

# Tryl [C++]
-------------------------------------------------------
#### Oct 2018 – Feb 2020

#### All-purpose library in which I do my best to produce high quality code. On my scale, this project is quite big. Here are some statistics about hand-written code:  

![](https://github.com/vincent-breysse/tryl/blob/master/screen/0.png)
![](https://github.com/vincent-breysse/tryl/blob/master/screen/1.png)

#### This project was very good at teaching me that implementing some features in a fresh code base has nothing to do with working in an environment carrying a certain past.  

#### More details : https://github.com/vincent-breysse/tryl

# Inari [Unity, C#]
-------------------------------------------------------
#### Jan 2019 – May 2019

#### 3rd person 3D platformer puzzle game we did during our 2nd year of studies.  
### Trailer
[![Trailer](https://img.youtube.com/vi/BZAh1M4cmQY/0.jpg)](https://www.youtube.com/watch?v=BZAh1M4cmQY)

#### More details : https://github.com/vincent-breysse/inari

## Radial [C++, SFML, Released on Steam] 
-------------------------------------------------------
#### Jan 2018 – Sep 2018
![](https://raw.githubusercontent.com/vincent-breysse/portfolio/main/assets/steam.png)

#### 2D action/reflexion platformer game we did during our 1st year of studies. The game has been released on Steam and comes with some successes to unlock. https://store.steampowered.com/app/1141850/Radial/  

### Trailer
[![Trailer](https://img.youtube.com/vi/dWEfaEr7UIQ/0.jpg)](https://www.youtube.com/watch?v=dWEfaEr7UIQ)

### Editor clip
[![Editor clip](https://img.youtube.com/vi/Q_NSUxumOyE/0.jpg)](https://www.youtube.com/watch?v=Q_NSUxumOyE)

#### More details : https://github.com/vincent-breysse/radial
