gl-modules
==========
A tutorial to working with WebGL using modular programming.

**WORK IN PROGRESS**


# Goals

* Introduce graphics programmers to a modular style of programming
* Emphasize code reuse
* Wrap common verbose tasks in modules to reduce code size
* .. but don't try to abstract stuff that doesn't need it
* Create a simpler and more expressive interface for WebGL programming from the bottom up

# Outline

## Preliminaries

Topics covered:

* Basic workflow with npm
* Working with binary data in JavaScript
* Linear algebra libraries

Modules introduced:

* [node.js](http://nodejs.org/)
* [npm](https://npmjs.org/)
* [ndarrays](https://github.com/mikolalysenko/ndarray)
* [gl-matrix](https://github.com/toji/gl-matrix)
* [browserify](https://github.com/substack/node-browserify)
* [beefy](https://github.com/chrisdickinson/beefy)

## Set up

Topics:

* Initializing WebGL

New modules:

* [game-shell](https://github.com/mikolalysenko/game-shell)
* [gl-now](https://github.com/mikolalysenko/gl-now)

## Drawing

Topics:

* Basic 2D drawing

New modules:

* [gl-buffer](https://github.com/mikolalysenko/gl-buffer)

## Shaders

Topics:

* Shaders
* Uniforms
* Attributes
* Varying variables

New modules:

* [gl-shader](https://github.com/mikolalysenko/gl-shader)

## Textures

Topics:

* Textures
* ndarrays for images
* Mipmapping

New modules:

* [gl-texture2d](https://github.com/mikolalysenko/gl-texture2d)

## Framebuffers

Topics:

* Framebuffers
* Offscreen rendering
* Feedback effects
* Basic GPGPU programming

New modules:

* [gl-fbo](https://github.com/mikolalysenko/gl-fbo)


## Coordinate Transformations

Topics:

* Active vs. passive transformations
* Coordinate transformations
* Homogenous coordinates
* Clipping frustum
* Cameras and model matrices


## Indexed geometry

Topics:

* Element arrays
* Simplicial complexes
* Meshes

New modules:

* [simplicial-complex](https://github.com/mikolalysenko/simplicial-complex)




# TO BE WRITTEN

Cameras

Mesh/geometry wrappers

Some prebaked materials?


# Links

http://acko.net/files/fullfrontal/fullfrontal/webglmath/online.html

http://www.khronos.org/registry/webgl/specs/latest/

# Credits
(c) 2013 Mikola Lysenko. MIT License