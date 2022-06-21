# Post Doc Challenge
The following is a small challenge in order for a future post doc position in our group.

# Project description
The idea is to create a graph classification approach based on a k-NN and the graph edit distance. In order to do this, we provide you with a small amount of graphs (see data folder), that you have to predict their class to. Libraries can be used. 

In the data folder you can find a certain amount of graphs in the .graphml format as well as two files, train.txt and validation.txt which contain the file names of the graphs for the corresponding sets.

# General Conditions
1. Choice of programming language is free.
2. The use of libraries is allowed.

# Specific conditions
1. For the graph edit distance computation, the node and edge deletion/ insertion costs should be set to 0.5 and the substitution costs to 1 if the nodes are not equal and 0 if they are equal.
2. For the k-NN, set the k to 3.

# Expected output
1. Predicted classes of the graphs
2. Graph Edit Distance matrix between the validation and training graphs


