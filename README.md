Maximum Flow
=======================

maximum flow problems involve finding a feasible flow through a single-source, single-sink flow network that is maximum.
The maximum flow problem can be seen as a special case of more complex network flow problems, such as the circulation problem. 
The maximum value of an s-t flow (i.e., flow from source s to sink t) is equal to the minimum capacity of an s-t cut (i.e., cut 
severing s from t) in the network, as stated in the max-flow min-cut theorem.


##Install

This library has the implementation of maximum flow algorithms to find the maximum flow in a directed graph 
G=[V,E].The following code snippet shows how to get the shortest path,

    

###Input
	3 3
	1 2 1
	2 3 2
	1 3 3

First integer is the total number of vertices |V| in the graph G. The next integer is the number of edges |E| in the graph.
Next |E| lines has the edges information (u, v, w). All inputs must be given through terminal.

###Output
	 
	 
  
##Project Contributor

* Dinesh Appavoo ([@DineshAppavoo](https://twitter.com/DineshAppavoo))
