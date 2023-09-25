# Soft-Decision-Tree
******
This is a pytorch implementation of Nicholas Frosst and Geoffrey Hinton's "Distilling a Neural Network Into a Soft Decision Tree".

The Soft decision tree in this implementation inferences by averaging the distribution over all the leaves, weighted by their respective path probabilities.

For inferencing with greatest path probability, please see https://github.com/kimhc6028/soft-decision-tree.

Original paper: https://arxiv.org/pdf/1711.09784.pdf


# Logic for constructing soft decision tree

******
The image below shows the logic for building a soft decision tree, where nodes are coded with (layer, position).


![image](https://github.com/robchenchen/Soft-Decision-Tree/assets/75876491/c3a115d7-2135-40a1-98e6-37f4af6560b1)

# Results
******

Without extensive tuning of hyperparameters, the tree with a depth of 8 was able to reach ~95% accuracy.

Feel free to ask questions, and please star if you find this useful.
