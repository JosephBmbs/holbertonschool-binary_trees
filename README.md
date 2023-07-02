
<p align="center">
  <img src="https://blog.penjee.com/wp-content/uploads/2015/11/binary-search-tree-sorted-array-animation.gif" alt="Project Logo">
  <h1 align="center">Binary Trees</h1>
  <h2 align="center">This repository contains the implementation of binary trees in C.</h2>
</p>

## Table of Contents

- [Introduction](#introduction)
- [Binary Tree](#binary-tree)
- [Binary Search Tree](#binary-search-tree)
- [AVL Tree](#avl-tree)
- [Max Binary Heap](#max-binary-heap)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we explore the concept of binary trees and their various types. We discuss the difference between a binary tree and a binary search tree, as well as the benefits of using binary trees over linked lists in terms of time complexity. Additionally, we cover the concepts of depth, height, and size of a binary tree, as well as the different traversal methods used to navigate through a binary tree. We also introduce the terms complete, full, perfect, and balanced binary trees.

## Binary Tree

A binary tree is a hierarchical data structure composed of nodes, where each node has at most two children, referred to as the left child and the right child. Each node contains an integer value and pointers to its parent, left child, and right child.

![Binary Tree Example](https://blog.penjee.com/wp-content/uploads/2015/11/binary-search-tree-insertion-animation.gif)

## Binary Search Tree

A binary search tree (BST) is a type of binary tree that follows a specific ordering property. In a BST, the value of every node in the left subtree is less than the value of the node, and the value of every node in the right subtree is greater than the value of the node. This property enables efficient searching, insertion, and deletion operations.

![Binary Search Tree Example](https://d18l82el6cdm1i.cloudfront.net/uploads/jxTW76g4MR-traversal.gif)

## AVL Tree

An AVL tree is a self-balancing binary search tree. It maintains an additional balance factor for each node, which is the difference between the heights of its left and right subtrees. When an insertion or deletion operation causes the balance factor of a node to violate the AVL tree property, rotations are performed to restore balance.

![AVL Tree Rotation](https://wkdtjsgur100.github.io/images/posts/rotation.gif)

## Max Binary Heap

A max binary heap is a complete binary tree where the value of each node is greater than or equal to the values of its children. It is commonly used to implement priority queues and heap sort algorithms.

![Max Binary Heap Example](https://esstudio.site/uploads/binaryheap.png)

## Usage

To use the binary tree implementations provided in this repository, include the `binary_trees.h` header file in your C program. The header file contains the necessary data structures and function prototypes.

```c
#include "binary_trees.h"

int main(void)
{
    // Your code here
    return 0;
}
```

Compile your program with the `binary_trees.c` source file.

```
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 main.c binary_trees.c -o binary_trees
```

## Contributing

Contributions to this repository are welcome. If you find any issues or would like to add new features or improvements, please create a pull request.
------------------------------------------------------------------------------------------------------

## Authors
This project Owner is -- Youssef Saad --