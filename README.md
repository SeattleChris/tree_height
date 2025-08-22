# tree_height

The height of a binary tree is the number of edges between the tree's root and its furthest leaf. For a given tree, determine it's height.

## Function Description

Complete the `height` function, which returns the height of a binary tree as an integer.

`height` has the following parameter(s):

* root: a reference to the root of a binary tree.

Returns:

* int denoting the height of the binary tree.

Note -The Height of binary tree with single node is taken as zero.

## Input Format

The first line contains an integer , the number of nodes in the tree. Next line contains  space separated integer where th integer denotes node[i].data.

Note: Node values are inserted into a binary search tree before a reference to the tree's root node is passed to the `height` function. In a binary search tree, all nodes on the left branch of a node are less than the node value. All values on the right branch are greater than the node value.

## Constraints

1 <= node, data[i] <= 20
1 <= n <= 20
