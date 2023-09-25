# Soft-Decision-Tree
This is a pytorch implementation of Nicholas Frosst and Geoffrey Hinton's "Distilling a Neural Network Into a Soft Decision Tree".

The Soft decision tree in this implementation inferences by averaging the distribution over all the leaves, weighted by their respective path probabilities.

For inferencing with greatest path probability, please see https://github.com/kimhc6028/soft-decision-tree.

Original paper: https://arxiv.org/pdf/1711.09784.pdf

![image](https://github.com/robchenchen/Soft-Decision-Tree/assets/75876491/644bd9c3-50f1-48f6-9c52-9924d701f9e9)
