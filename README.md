![](https://camo.githubusercontent.com/116552100f67e47684f708549a7e031689d13ac4/68747470733a2f2f692e696d6775722e636f6d2f544e4c6d7045722e6a7067)
# Parallax
Parallax is a custom terrain shader for Kerbal Space Program that combines tessellation and displacement mapping to create realistic planetary surfaces.

Watch the trailer here: https://www.youtube.com/watch?v=7TjmvMywTN4

## Features
Parallax completely replaces the terrain shader used in the normal game in favour of more and better features, including:

* Tessellation
* Self-shadowing
* Accurate lighting
* Accurate normal mapping
* Support for multiple lights
* Reflections
* Specular highlights
* Metallic materials
* Influence mapping

## Improvements
The shader that Squad uses for Kerbal Space Program is extremely limited. You can only assign 2 textures that work unless you opt to use an extremely complicated 'Atlas' shader that was introduced in 1.9. We will pretend that the Atlas shader doesn't exist because it's only used on Kerbin and it is extremely unoptimized.

Parallax improves upon the stock shader in a number of ways, for example:
* Normal mapped lighting is accurate and faces the right way on a surface at any angle
* Tessellation allows surfaces to have much more complexity, allowing for the creation of lifelike planet surfaces
* Texture blending is a much smoother transition and varies based on the distance from the camera
* You can have a much greater amount of control over the planet - You have a low, mid, high and steep texture to use
* Complete control over how much colour of a texture to apply to the surface VS how much colour of the surface to retain (using an influence map). This prevents your grass from changing colour on brown terrain, but lets you change the sand colour as it varies with the planet's surface colour.

