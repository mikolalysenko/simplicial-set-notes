simplicial-set-notes
====================

## Graphs in higher dimensions

[Graphs](http://en.wikipedia.org/wiki/Graph) are fundamental in computer science. Everywhere you go, you hear people talking about networks, connections and other graph like euphemisms.  Graphs are used to model all sorts of things:

* [Social networks](http://en.wikipedia.org/wiki/Social_network)
* [Distributed systems](http://en.wikipedia.org/wiki/Computer_network)
* [Ecological networks](http://en.wikipedia.org/wiki/Ecological_network)
* [The human brain](http://en.wikipedia.org/wiki/Neural_network)

But graphs are 1 dimensional structures (even though they can be embedded in higher dimensional spaces), and in geometry they are often insufficient to describe the sorts of objects which we are interested in, like surfaces and solids. However, topology in 1-dimension can be deceptively simple, and in carrying out the generalization of graphs to higher dimensional spaces there are multiple possibilities.

### Cell complexes

There are multiple ways to generalize graphs, though the most successful has been the concept of a [cell complex](http://en.wikipedia.org/wiki/Abstract_cell_complex). Cell complexes are made out of simple units called *cells*, which are then glued together to form a larger and more complex space. Types of cell complexes differ in the sorts of cells that they allow and the ways in which they are glued together. For example, [CW complexes](http://en.wikipedia.org/wiki/CW_complex) are a popular mathematical formulation for spaces in [homotopy theory](http://en.wikipedia.org/wiki/Homotopy). In a CW complex, cells can be any [contractible space](http://en.wikipedia.org/wiki/Contractible_space) (picture: a blob/potato), and the binding relations are arbitrary [homeomorphisms](http://en.wikipedia.org/wiki/Homeomorphism) (picture: stretch/squish the blobs and glue them together). This generality is mathematically convenient for constructing and reasoning about spaces on paper, but it can be hard to translate into a computer.

### Simplicial complexes

Instead, more restricted types of cell complexes are often more useful when it comes down to crunching numbers. The most popular digital representation of spaces are [simplicial complexes](http://en.wikipedia.org/wiki/Simplicial_complex). Simplicial complexes are widely used in graphics and engineering, and they are the representation that we will be focusing.  The basic idea in a simplicial complex is to build up a space by gluing together [simplices](http://en.wikipedia.org/wiki/Simplex). Briefly,

* A 0D simplex is a point
* A 1D simplex is an edge
* A 2D simplex is a [triangle](http://en.wikipedia.org/wiki/Triangle)
* A 3D simplex is a [tetrahedron](http://en.wikipedia.org/wiki/Tetrahedron)
* ...

The connection between graphs and simplicial complexes should be clear, since a graph is a 1D simplicial complex is exactly a graph.

### Other types of cell complexes

Finally, it is worth briefly mentioning a few of the other options for encoding cells (though we won't say much about them in detail):

* [Cubical complexes](http://inperc.com/wiki/index.php?title=Cubical_complex): Cubical complexes represent geometry as a union of boxes or hypercubes (think Minecraft).  For certain types of boxy geometry, they can be much more eficient than simplices, but are more limited in the sorts of shapes they can represent.
* [Whitney regular stratification](en.wikipedia.org/wiki/Stratification_%28mathematics%29): Stratifications represent spaces as a decomposition of semi-algebraic sets, allowing for smooth shapes like polynomial curves, surfaces and so on.

## Variations on simplicial complexes

In graph theory, one encounters many variations on the concept of a graph, which have subtly different properties:

* [Undirected graphs](http://en.wikipedia.org/wiki/Graph_(mathematics)#Undirected_graph)
* [Directed graphs](http://en.wikipedia.org/wiki/Graph_(mathematics)#Directed_graph)
* [Multigraphs](http://en.wikipedia.org/wiki/Graph_(mathematics)#Multigraph)
* [Graphs with loops](en.wikipedia.org/wiki/Loop_%28graph_theory%29)

These properties generalize in various ways to simplicial complexes, which we shall now sketch out briefly.

### Simplicial complexes



### Oriented simplicial complexes

### Delta sets

### Simplicial sets



## Topological queries

### Skeletons

### Face maps

### Incidence maps

### Data structures



## Planar graphs and triangulations

### Duality

### Polygons

### Euler's formula

### Half-edge
