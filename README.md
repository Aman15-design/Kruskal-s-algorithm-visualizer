# Kruskal-s-algorithm-visualizer
# What is Minimum Spanning Tree? 
Given a connected and undirected graph, a spanning tree of that graph is a subgraph that is a tree and connects all the vertices together. A single graph can have many different spanning trees. A minimum spanning tree (MST) or minimum weight spanning tree for a weighted, connected, undirected graph is a spanning tree with a weight less than or equal to the weight of every other spanning tree. The weight of a spanning tree is the sum of weights given to each edge of the spanning tree.
#
A minimum spanning tree has (V – 1) edges where V is the number of vertices in the given graph. 
See this for applications of MST.
# Algorithm
1. Sort all the edges in non-decreasing order of their weight. 
2. Pick the smallest edge. Check if it forms a cycle with the spanning tree formed so far. If cycle is not formed, include this edge. Else, discard it. 
3. Repeat step#2 until there are (V-1) edges in the spanning tree.
# ![kruskal 1](https://user-images.githubusercontent.com/69804663/130104530-d3a61932-569b-4753-9e33-b4aea7f916ab.PNG)
#
