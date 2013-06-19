gl-modules
==========
A tutorial to working with WebGL using modular programming.

**WORK IN PROGRESS**


## Goals

* Teach WebGL with minimal amount of magic
* Wrap common verbose tasks in modules to reduce code size
* .. but don't try to abstract stuff that doesn't need it
* Emphasize code reuse

### Why modules instead of frameworks

* Reusable - the same module can serve multiple functions
* Replaceable - if a module is broke or a better implementation is found, swap it out
* Testable - smaller interfaces mean less surface to test and fewer possibilities for exploitation or errors
* [Simpler](http://www.infoq.com/presentations/Simple-Made-Easy) - fewer lines of code, easier to communicate their intention and define their purpose

The node.js philosophy is to strive to break things down into the simplest possible units.  Then build more complex things by incrementally combining these pieces into successively bigger structures.  This is the approach taken in this tutorial to WebGL

### Why bother wrapping WebGL

Parts of WebGL are pretty good, but other parts are pretty ugly and asinine.  Many methods involve lots of [redundant parameters](http://www.khronos.org/opengles/sdk/docs/man/xhtml/glTexImage2D.xml), have [inconsistent](http://www.khronos.org/opengles/sdk/docs/man/xhtml/glDrawArrays.xml) [orderings](http://www.khronos.org/opengles/sdk/docs/man/xhtml/glDrawElements.xml) for arguments and obscure/inconsistent naming conventions and capitalizations (for example [Frame **b** uffer](http://www.khronos.org/registry/webgl/specs/latest/#5.14.6) vs [drawing **B** uffer](http://www.khronos.org/registry/webgl/specs/latest/#THE_DRAWING_BUFFER) ), or serve absolutely no [useful](http://www.khronos.org/opengles/sdk/docs/man/xhtml/glIsBuffer.xml) [purpose](http://www.khronos.org/opengles/sdk/docs/man/xhtml/glIsTexture.xml).

On the other hand, there are also parts of WebGL that are so simple that it would be pointless to wrap them.  For example, there is no clear need to create a wrapper for the [state API](http://www.khronos.org/registry/webgl/specs/latest/#5.14.3), and so we won't ever bother doing so.

The advantage to taking a modular approach to wrapping WebGL is that we can paper over only the parts of the API which are ugly or inconsistent, and leave the rest of the system intact.  It is also easy to mix wrapped WebGL code with other modules that adopt a similar low level approach, giving a very flexible and robust system for building high performance, low overhead WebGL applications.

## Assumed knowledge

* Basic understanding of JavaScript
* Some familiarity with graphics concepts will be helpful

# Outline

### Preliminaries

Topics covered:

* CommonJS modules
* npm package management
* browserify
* Interactive work flow, beefy and live-reload
* Deployment/hosting options

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