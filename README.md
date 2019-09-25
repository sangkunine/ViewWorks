# ViewWorks

![](https://img.shields.io/badge/minzipped_size-1.7MB-blue)
![](https://img.shields.io/badge/node-v10.14.1-yellow)
![](https://img.shields.io/badge/npm-6.4.1-yellow)
![](https://img.shields.io/badge/webpack-4.38.0-yellow)
![](https://img.shields.io/badge/three.js-r106-green)

**ViewWorks** is a web-based 3D model viewer for a real-time rendering of various kinds of 3D model files using the popular javascript library, [three.js](https://threejs.org/). It will be upgraded for faster file loading and rendering, and more features will continue to be inserted for further analysis.

## Supported file formats
JSON,
OBJ(+MTL),
STL,
PLY,
DAE(COLLADA),
GLTF,
GLB,
AMF,
3MF,
WRL(VRML),
FBX

Note that 11 most popular file formats can be loaded and rendered. The figures below show the rendering result after loading the sample models.
<div style="text-align: center;">
<img src="https://sangkunine.github.io/viewWorks/images/samples/bike.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/birdInTreeOnHill.png" width="24%" style="margin: 1px">
<img src="https://sangkunine.github.io/viewWorks/images/samples/Build_a_city.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/BusterDrone.png" width="24%" style="margin: 1px">
<img src="https://sangkunine.github.io/viewWorks/images/samples/Dragon_and_phoenix_statuette.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/Hovering_helicopter.png" width="24%" style="margin: 1px">
<img src="https://sangkunine.github.io/viewWorks/images/samples/lost_empire.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/sponza.png" width="24%" style="margin: 1px">
</div>

## Website
You can run this application at the website:  https://sangkunine.github.io/viewWorks/.

## Highlighted Features
- Underlying technologies
WebGL(three.js), GLSL Shaders using ray-marching technique
- Drag & drop
Any of 3D model files can be loaded to this application by a drag & drop manner.
- Three types of background
In this viewer, three kinds of textures for background are supported. They are 8 wallpaper textures, 6 cubemap textures, and 4 dynamic textures.
- PBR-based floors:
These are base floors for improving the visual appearance of the loaded model. These are rendered using PBR techniques. One of these is a circular plate with mirror or glass features.
- Others
	- Hemisphere light & directional light
	- Shadow maps using the percentage-closer soft shadows technique
	- Auto-fitting the loaded model to the window

## User Interface

- Menu bar
There is no menu bar to maximize a screen area.

- Drag & drop
To load a model consisting of multiple files, you can select multiple files in the file explorer and drag & drop them into your web browser.

- Keyboard
The key **1** and **2** allow us to change a background and a floor, respectively.
The key **p** allows us to play the animation of a loaded model if available, and **o** pause the animation action. (cf: If you press the key **o** again, the paused action continues.)

- Mouse
You can control a camera to take a closer look at the loaded models by:
	-pressing left button & moving mouse for camera rotating,
	-pressing right button & moving mouse for camera panning,
	-scrolling mouse wheel for camera zooming (in/out).

## Future works
- Function to load a new model file format (unsupported by this viewer) such as 3DS, IGES, STEP, etc.
- Function to measure the Euclidean distance between clicked two points.
- Function to calculate mass properties such as surface area and volume size.
- Function to count the number of vertices or faces.
- Function to compute the size of axis-aligned bounding box or the radius of bounding sphere.
- Function to render the loaded model in wireframe style.
- Function to map (transform) the colors of the loaded models for further analysis on geometric properties such as Gaussian curvatures.

## Question or suggestion
Please contact us at <info@nova-graphix.com> for any question or suggestion.

Thank you for reading this description on this 3D viewer, called **ViewWorks**, developed by [NovaGraphix, Co.](https://www.nova-graphix.com/) Note that we will continue to add new features. Anyone can use it for free without any restrictions.