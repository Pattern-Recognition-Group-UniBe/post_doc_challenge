# Post Doc Challenge
The following task is a small challenge to overcome when applying for a post-doctoral position in our group.

# Project description
The idea is to create a graph classification approach based on a k-NN and Graph Edit Distance (GED) (https://en.wikipedia.org/wiki/Graph_edit_distance). We provide a small set of graphs (see data folder) whose class you need to predict.

In the data folder you can find a certain amount of graphs in the graphml format as well as two files, train.txt and test.txt which contain the file names of the graphs for the corresponding sets.

# General Conditions
1. Choice of programming language is free (in our group we mainly work with python).
2. The use of libraries is allowed.

# Specific conditions
1. For the computation of GED, the node and edge deletion/insertion costs should be set to 0.5 and the substitution costs to 1 if the nodes are not equal and 0 otherwise.
2. No optimization is required for the k-NN, set the parameter k to 3.

# Expected output
1. Predicted classes of the graphs in the form of a csv file with two columns (C1 graph_name, C2 predicted_class)
2. Graph Edit Distance matrix between the test and training graphs in the form of a csv file.
3. For examples of the output format, see "example_output" folder (the results presented there are not actual results).
