# binarysearchtree

Assignment 3 part 2 source code template. The purporse of this assignment is to create binary tree which can:
1. add root
2. add left child node
3. add right child node
4. count all leaves
5. get sibling
6. get a subtree
7. discard a subtree
In our case there aren't any node removal, in typical BST or RBT when a node is discarded its descendant tree will get attached to parent. But since we are only implementing a binary tree node removal means its whole subtree is removed. 

Your task is fulfilling all todo in 
1. structure/mod.rs
2. main.rs
3. tool/mod.rs

To debug the tree, you need to complete todo in tool/mod.rs. Which will implement the tree in [graphviz dot language](https://graphviz.org/doc/info/lang.html). The dot notation is relatively straightforward and easy to understand. In fact you don't need to illustrate the graph in a drawing, just output them to dot graphviz notation as a model.
