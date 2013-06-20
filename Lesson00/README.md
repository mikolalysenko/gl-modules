# Lesson 0: Perliminaries

## About this tutorial


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


## Introduction to the CommonJS

### node.js and npm

### browserify


## Typical workflow

### beefy

