# Part IA Introduction to Graphics: Ray Tracer
A simple ray tracer written in Java for tick 1 of the Part IA Introduction to Graphics course. The program renders a 2D image of a 3D scene specified in a `.xml` file.

<p float="left">

<img src="https://github.com/meganelisabethfinch/Graphics_IA_RayTracer/blob/master/scene3_reference.png" alt="A render of a custom scene" width="49%" />
<img src="https://github.com/meganelisabethfinch/Graphics_IA_RayTracer/blob/master/scene1_reference.png" alt="A render of a test scene" width="49%"  /> 
</p>

## :clipboard: Task

For this task, we were given skeleton code to work with. I implemented the following:
* Ray-plane intersections in `Plane.intersectionWith(...)`
* Ray-sphere intersections in `Sphere.intersectionWith(...)`
* A Phong shading model, which calculates the direct illumination at a point based on ambient and point light sources present in the scene, in `Renderer.illuminate(...)`
* Shadow rays, also in `Renderer.illuminate(...)`
* Recursive ray tracing for reflective surfaces in `Renderer.trace(...)`

## :computer: Solution
