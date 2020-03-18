# ViewWorks

![](https://img.shields.io/badge/minzipped_size-1.6MB-blue)
![](https://img.shields.io/badge/node-v10.14.1-yellow)
![](https://img.shields.io/badge/npm-6.4.1-yellow)
![](https://img.shields.io/badge/webpack-4.38.0-yellow)
![](https://img.shields.io/badge/three.js-r114-green)

**ViewWorks** is a web-based 3D model viewer for a fast rendering of the most common 3D model files using the popular javascript library, [three.js](https://threejs.org/). It will be upgraded for faster file loading and rendering, and more features will continue to be inserted for further analysis.

## Supported file formats
JSON, OBJ(+MTL), STL, PLY, DAE(COLLADA),
GLTF, GLB, AMF, 3MF, WRL(VRML), FBX,
3DS, DRC, KMZ, MD2, SVG, VTK

Note that 17 most popular file formats can be loaded and rendered. The figures below show the rendered images after loading the sample models.
<div style="text-align: center;">
<img src="https://sangkunine.github.io/viewWorks/images/samples/bike.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/birdInTreeOnHill.png" width="24%" style="margin: 1px">
<img src="https://sangkunine.github.io/viewWorks/images/samples/Build_a_city.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/BusterDrone.png" width="24%" style="margin: 1px">
<img src="https://sangkunine.github.io/viewWorks/images/samples/Dragon_and_phoenix_statuette.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/Hovering_helicopter.png" width="24%" style="margin: 1px">
<img src="https://sangkunine.github.io/viewWorks/images/samples/lost_empire.png" width="24%" style="margin: 1px"> <img src="https://sangkunine.github.io/viewWorks/images/samples/sponza.png" width="24%" style="margin: 1px">
</div>

## Website
You can run this application at the website: https://sangkunine.github.io/viewWorks/.

## Highlighted features
- Underlying technologies<br>
WebGL(three.js), Physically-based rendering, GLSL Shaders using ray-marching technique
- Background<br>
In this viewer, three different textures are used as a background. They are wallpaper textures, cube map textures, and animated textures.
- PBR-based floors<br>
These are base floors for improving the visual appearance of the loaded model. These are rendered using PBR techniques. One of these is a circular plate with mirror or glass features.
- Drag & drop<br>
3D model files can be loaded to this application by a drag & drop manner.
- Lights & Shadow
	- Hemisphere light & directional light
	- Shadow maps using the percentage-closer soft shadows technique
- Perspective Camera
	- Fitting the camera to the size of the loaded models
	- Controls the camera to orbit around the models

## Unique Selling Proposition
- The 3D model styler embedded in ViewWorks allows you to examine the inner structure of 3D models.
- ViewWorks helps you to improve the visual appearance of 3D models by changing the material properties or material itself.
- ViewWorks allows you to share or embed 3D models anywhere online.

## User interface

- Menu bar<br>
There is no menu bar to maximize a screen area.

- Drag & drop<br>
To load a model consisting of multiple files, you can select multiple files in the file explorer and drag & drop them into your web browser.

- Keyboard<br>
The key **1** and **2** allow us to change a background and floor model, respectively.
The key **p** allows us to play the animation of loaded models if available, and **o** pause the animation action. (If you press the key **o** again, the paused action continues.)

- Mouse<br>
You can control a camera to take a closer look at the loaded models by:<br>
	-pressing left button & moving mouse for camera rotating,<br>
	-pressing right button & moving mouse for camera panning,<br>
	-scrolling mouse wheel for camera zooming (in/out).

## Future works
- Function to load a new model file format such as IGES, STEP, etc.
- Function to measure the Euclidean distance between two clicked points.
- Function to calculate mass properties such as surface area and volume size.
- Function to count the number of vertices or faces of the loaded models if available.
- Function to compute the size of an axis-aligned bounding box or the radius of a bounding sphere of the model.
- Function to render the loaded model in a wireframe style.
- Function to transform the colors of the loaded models for further analysis of geometric properties such as Gaussian curvatures.

## Question or suggestion
Please contact us at <info@nova-graphix.com> for any question or suggestion.

Thank you for reading the above description on **ViewWorks**, developed by [NovaGraphix, Co.](https://www.nova-graphix.com/) Note that we will continue to add new features and technologies. Anyone can use it for free without any restrictions.