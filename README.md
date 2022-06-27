# Post Doc Challenge
The following is a small challenge in order for a future post doc position in our group.

# Project description
The idea is to create a graph classification approach based on a k-NN and the graph edit distance. To do this, we provide a small set of graphs (see data folder) whose class you need to predict.

In the data folder you can find a certain amount of graphs in the .graphml format as well as two files, train.txt and test.txt which contain the file names of the graphs for the corresponding sets.

# General Conditions
1. Choice of programming language is free. In our group we mainly work with python.
2. The use of libraries is allowed.

# Specific conditions
1. For the graph edit distance computation, the node and edge deletion/ insertion costs should be set to 0.5 and the substitution costs to 1 if the nodes are not equal and 0 if they are equal.
2. For the k-NN, set the k to 3.

# Expected output
1. Predicted classes of the graphs in the form of a csv file with two columns. 1. 
2. Graph Edit Distance matrix between the test and training graphs in the form of a .csv file.
3. For examples of the output format, see example_output folder


