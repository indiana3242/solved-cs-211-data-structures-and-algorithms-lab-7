Download Link: https://assignmentchef.com/product/solved-cs-211-data-structures-and-algorithms-lab-7
<br>
The objective of this assignment is to implement Kruskal’s algorithm to find a minimum spanning tree (MST) of the given connected edge-weighted undirected graph.




<h1>Inputs</h1>




Your program should accept an input file as command-line argument. A typical execution of your program will be ‘./a.out sample.graph’.




The input file represents a connected undirected graph with integer weights on edges. Every node (vertex) in the graph is labelled uniquely with a non-negative integer. Every line in the input file is of the form ​<em>x y w</em>​, which represents an edge between node <em>x</em>​ and node <em>y</em>​ ​, where the weight of the edge is ​<em>w</em>​. No edge is repeated in the input file. Since edge-weights are unique and you are using Kruskal’s algorithm, it is guaranteed that the output is unique.




<h1>Task</h1>

<strong> </strong>

Implement Kruskal’s algorithm to find a minimum spanning tree of the given connected, weighted, and undirected graph. It is recommended that you use disjoint-set forest data structure with union-by-rank and path-compression heuristics. But a simpler implementation of the algorithm will also be accepted with full credits.




<h1>Output</h1>




Your program should create a file named ‘mst.txt’. Every line in the output file should be of the form ​<em>x y w</em>​, which represents an edge ​<em>xy</em> with weight ​<em>w</em> in the minimum spanning tree. The edges should be present in the file in the non-decreasing order of their weights.