Modules for graphics programming
================================

## Basic modules

### Set up

* Input handling, ticking: [`game-shell`](https://github.com/mikolalysenko/game-shell#api)
* WebGL set up: [`gl-now`](https://github.com/mikolalysenko/gl-now#api)

### Memory and multidimensional arrays

* Pooling: [`typedarray-pool`](https://github.com/mikolalysenko/typedarray-pool#api)
* Data structure: [`ndarray`](https://github.com/mikolalysenko/ndarray#api)
* Raster operations: [`cwise`](https://github.com/mikolalysenko/cwise/#requirecwiseuser_args)
* Utility methods: [`ndarray-ops`](https://github.com/mikolalysenko/ndarray-ops#conventions)
* Initialization: [`ndarray-fill`](https://npmjs.org/package/ndarray-fill)
* Interoperability: [`ndarray-pack`](https://npmjs.org/package/ndarray-pack), [`ndarray-unpack`](https://npmjs.org/package/ndarray-unpack)

### WebGL wrappers

* Shaders: [`gl-shader`](https://github.com/mikolalysenko/gl-shader#api)
* Buffers: [`gl-buffer`](https://github.com/mikolalysenko/gl-buffer#api)
* Textures: [`gl-texture2d`](https://github.com/mikolalysenko/gl-texture2d#api)
* Framebuffers: [`gl-fbo`](https://github.com/mikolalysenko/gl-fbo#api)
* Vertex arrays: [`gl-vao`](https://github.com/mikolalysenko/gl-vao#api)

### Arithmetic

* Linear algebra: [`gl-matrix`](https://github.com/toji/gl-matrix)
* Bit twiddling: [`bit-twiddle`](https://npmjs.org/package/bit-twiddle)
* Bit interleave: [`bit-interleave`](https://npmjs.org/package/bit-interleave)

## Data

### File formats and parsers

* Images: [`get-pixels`](https://github.com/mikolalysenko/get-pixels), [`save-pixels`](https://npmjs.org/package/save-pixels)
* Volume graphics: [`nrrd-js`](https://npmjs.org/package/nrrd-js), [`ndarray-to-binvox`](https://npmjs.org/package/ndarray-to-binvox), [`minecraft-mca`](https://npmjs.org/package/minecraft-mca)
* Meshes: [`parse-ply`](https://npmjs.org/package/parse-ply), [`write-ply`](https://npmjs.org/package/write-ply), [`write-vrml`](https://npmjs.org/package/write-vrml), [`parse-obj`](https://npmjs.org/package/parse-obj)

### Test data

* Meshes: [`bunny`](https://npmjs.org/package/bunny), [`teapot`](https://npmjs.org/package/teapot)
* Images: [`lena`](https://npmjs.org/package/lena), [`isabella-texture-pack`](https://npmjs.org/package/isabella-texture-pack)

### Data generators

* Symmetric polytopes: [`conway-hart`](https://npmjs.org/package/conway-hart)

## Discrete algorithms and data structures

### Searching

* Bisection: [`bisect`](https://npmjs.org/package/bisect)
* Binary search: [`binary-search-bounds`](https://npmjs.org/package/binary-search-bounds)

### Sorting

* Sort ndarrays: [`ndarray-sort`](https://npmjs.org/package/ndarray-sort)
* 2-way merge: [`binary-merge`](https://npmjs.org/package/binary-merge)

### Priority queue

* Binary heap: [`heap`](https://npmjs.org/package/heap)

### Binary search trees

* Functional red-black tree: [`functional-red-black-tree`](https://npmjs.org/package/functional-red-black-tree)
* Imperative red-black tree: [`bintrees`](https://npmjs.org/package/bintrees)

### Permutations

* Ranking: [`permutation-rank`](https://npmjs.org/package/permutation-rank)
* Inversion: [`invert-permutation`](https://npmjs.org/package/invert-permutation)

### Dynamic graphs

* Incremental connectivity: [`union-find`](https://npmjs.org/package/union-find)
* Dynamic connectivity: [`dynamic-forest`](https://npmjs.org/package/dynamic-forest)

### Minimum spanning tree

* Kruskal's algorithm: [`kruskal`](https://npmjs.org/package/kruskal)

### Directed graphs

* Strongly connected components: [`strongly-connected-components`](https://npmjs.org/package/strongly-connected-components)

### Bipartite graphs

* Maximum matching: [`bipartite-matching`](https://npmjs.org/package/bipartite-matching)
* Minimum vertex cover: [`bipartite-vertex-cover`](https://npmjs.org/package/bipartite-vertex-cover)
* Maximum independent set: [`bipartite-independent-set`](https://npmjs.org/package/bipartite-independent-set)

### Lists

* Ordered file maintenance [`order-maintenance`](https://npmjs.org/package/order-maintenance)
* Version maintenance [`version-tree`](https://npmjs.org/package/version-tree)

### Paths

* A-star search: [`a-star`](https://npmjs.org/package/a-star)

### Hashing

* Integer hashing: [`hash-int`](https://npmjs.org/package/hash-int)
* k-way hashing: [`k-hash`](https://npmjs.org/package/k-hash)
* Murmur Hash: [`murmurhash-js`](https://npmjs.org/package/murmurhash-js)

### SAT solvers

* 2-SAT: [`2-sat`](https://npmjs.org/package/2-sat)
* HORN-SAT: [`horn-sat`](https://npmjs.org/package/horn-sat)
* Back tracking: [`backtrack`](https://npmjs.org/package/backtrack)

## Numerical methods

### Basic linear algebra

* [`ndgemm`](https://npmjs.org/package/ndgemm)

### Linear solvers

* [`conjugate-gradient`](https://npmjs.org/package/conjugate-gradient)

### Quadrature

* [`gauss-quadrature`](https://npmjs.org/package/gauss-quadrature)

### Interpolation and splines

* [`cubic-hermite`](https://npmjs.org/package/cubic-hermite)
* [`bezier`](https://npmjs.org/package/bezier)
* [`splines`](https://npmjs.org/package/splines)

### Polynomials

* [`horner`](https://npmjs.org/package/horner)
* [`durand-kerner`](https://npmjs.org/package/durand-kerner)
* [`poly-derivative`](https://npmjs.org/package/poly-derivative)
* [`poly-mult`](https://npmjs.org/package/poly-mult)
* [`poly-mult-fft`](https://npmjs.org/package/poly-mult-fft)

### Fourier transform

* [`ndarray-fft`](https://npmjs.org/package/ndarray-fft)
* [`ndarray-complex`](https://npmjs.org/package/ndarray-complex)
* [`phase-align`](https://npmjs.org/package/phase-align)
* [`ndarray-convolve`](https://npmjs.org/package/ndarray-convolve)

### Image processing

* [`distance-transform`](https://npmjs.org/package/distance-transform)
* [`ball-morphology`](https://npmjs.org/package/ball-morphology)
* [`image-rotate`](https://npmjs.org/package/image-rotate)
* [`ndarray-warp`](https://npmjs.org/package/ndarray-warp)

## Geometry processing

### Basic topology

* [`simplicial-complex`](https://npmjs.org/package/simplicial-complex)
* [`stars`](https://npmjs.org/package/stars)
* [`euler-characteristic`](https://npmjs.org/package/euler-characteristic)

### Robust predicates

* [`robust-orientation`](https://npmjs.org/package/robust-orientation)
* [`robust-point-in-simplex`](https://npmjs.org/package/robust-point-in-simplex)
* [`robust-in-sphere`](https://npmjs.org/package/robust-in-sphere)
* [`robust-segment-intersect`](https://npmjs.org/package/robust-segment-intersect)

### Non-robust predicates

* [`almost-equal`](https://npmjs.org/package/almost-equal)
* [`polytope-closest-point`](https://npmjs.org/package/polytope-closest-point)
* [`box-frustum`](https://npmjs.org/package/box-frustum)
* [`circumcenter`](https://npmjs.org/package/circumcenter)
* [`barycentric`](https://npmjs.org/package/barycentric)
* [`point-in-simplex`](https://npmjs.org/package/point-in-simplex)
* [`split-polygon`](https://npmjs.org/package/split-polygon)
* [`segseg`](https://npmjs.org/package/segseg)
* [`point-in-polygon`](https://github.com/substack/point-in-polygon)

### Mesh repair

* [`fuse-vertices`](https://npmjs.org/package/fuse-vertices)

### Convex hull

* [`quick-hull-2d`](https://npmjs.org/package/quick-hull-2d)
* [`qhull-js`](https://npmjs.org/package/qhull-js)

### Triangulations

* [`delaunay-triangulate`](https://npmjs.org/package/delaunay-triangulate)
* [`voronoi-diagram`](https://npmjs.org/package/voronoi-diagram)

### Range searching

* [`interval-tree-1d`](https://npmjs.org/package/interval-tree-1d)
* [`static-range-query`](https://npmjs.org/package/static-range-query)

### Collision detection

* [`n-body-pairs`](https://github.com/mikolalysenko/n-body-pairs)

### Solid modeling

* [`isosurface`](https://github.com/mikolalysenko/isosurface)
* [`rle-core`](https://github.com/mikolalysenko/rle-core)
* [`voxelize`](https://npmjs.org/package/voxelize)

### 3D printing

* [`shapeways`](https://npmjs.org/package/shapeways)


## Audio processing

### Synthesis

* [`mespeak`](https://npmjs.org/package/mespeak)

### Analysis

* [`detect-pitch`](https://npmjs.org/package/detect-pitch)

### Modification

* [`pitch-shift`](https://npmjs.org/package/pitch-shift)