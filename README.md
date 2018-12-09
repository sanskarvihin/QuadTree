# QuadTree

A quadtree is a tree in which each internal (not leaf) node has four children.

![alt text](https://github.com/sanskarvihin/QuadTree/blob/master/quadtree.png)

Consider the following problem: your need to store a number of points (each point is a pair of X and Y coordinates) and then you need to answer which points lie in a certain rectangular region. A naive solution would be to store the points inside an array and then iterate over the points and check each one individually. This solution runs in O(n) though. Better Approach would be to use QuadTree. Quadtrees are most commonly used to partition a two-dimensional space by recursively subdividing it into four regions(quadrants).
