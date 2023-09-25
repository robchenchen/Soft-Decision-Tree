# Neural-Decision-Tree
This is a pytorch implementation of Nicholas Frosst and Geoffrey Hinton's "Distilling a Neural Network Into a Soft Decision Tree"

The neural decision tree in this implementation inferences by averaging the distribution over all the leaves, weighted by their respective path probabilities.

For inference with greatest path probability, please see https://github.com/kimhc6028/soft-decision-tree

Original paper: https://arxiv.org/pdf/1711.09784.pdf
