# Decision Tree
A decision tree is one of the most powerful tools of supervised learning algorithms used for both classification and regression tasks.it is like a flow chart or a tree having root nodes, internal nodes and leaf nodes. 
## terminologies in decision tree
### root node:
it contain the original dataset and split conditions.
### decision nodes:
decision nodes are internal nodes that contain conditions for splitting the dataset further on basis of attribute selection measures(ASM).
### terminal nodes
those nodes which don't have child node. mostly contain homogenuous data(one class only).
### entropy
it the measure of randomness and uncertainity in the dataset. it's value ranges from 0-1.0 means less entropy and 1 is the highest entropy value.
### information gain
it is the measure of information state of a node. it decides which split condition acting on a node is more preferrable. it is measured using entropy of parent node and the child nodes. the split having highest information gain will be cansidered more preferrable. it values ranges from 0-1.
#### implementation in python
I implemeted decision tree in python using numpy, pandas and scikit.
##### link for the code file is given below;
https://github.com/sajalozair/summerAIinternship/blob/main/day8/Decision%20tree%20algorithm.ipynb

