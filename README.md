gl-modules
==========
A tutorial to working with WebGL using modular programming.

**WORK IN PROGRESS**


# Goals

* Teach WebGL with minimal amount of magic
* Wrap common verbose tasks in modules to reduce code size
* .. but don't try to abstract stuff that doesn't need it
* Emphasize code reuse

# Outline

### Preliminaries

Topics covered:

* CommonJS modules
* npm package management
* browserify
* Interactive work flow, beefy and live-reload

Modules introduced:

* [node.js](http://nodejs.org/)
* [npm](https://npmjs.org/)
* [browserify](https://github.com/substack/node-browserify)
* [beefy](https://github.com/chrisdickinson/beefy)

### Set up

Topics:

* Initializing WebGL

New modules:

* [game-shell](https://github.com/mikolalysenko/game-shell)
* [gl-now](https://github.com/mikolalysenko/gl-now)

### 2D Drawing

Topics:

* Basic 2D drawing
* Buffers
* Shaders
* Uniforms
* Attributes
* Varying variables

New modules:

* [gl-buffer](https://github.com/mikolalysenko/gl-buffer)
* [gl-shader](https://github.com/mikolalysenko/gl-shader)

### Textures

Topics:

* Textures
* ndarrays for images
* Mipmapping

New modules:

* [gl-texture2d](https://github.com/mikolalysenko/gl-texture2d)

### Framebuffers

Topics:

* Framebuffers
* Offscreen rendering
* Feedback effects
* Basic GPGPU programming

New modules:

* [gl-fbo](https://github.com/mikolalysenko/gl-fbo)

### Coordinate Transformations

Topics:

* Active vs. passive transformations
* Coordinate transformations
* Homogenous coordinates
* Clipping frustum
* Cameras and model matrices

New modules:

* [gl-matrix](https://github.com/toji/gl-matrix)

### Indexed geometry

Topics:

* Element arrays
* Simplicial complexes
* Meshes

New modules:

* [ndarrays](https://github.com/mikolalysenko/ndarray)
* [simplicial-complex](https://github.com/mikolalysenko/simplicial-complex)


# Links

http://acko.net/files/fullfrontal/fullfrontal/webglmath/online.html

http://www.khronos.org/registry/webgl/specs/latest/

# Credits
(c) 2013 Mikola Lysenko. MIT License