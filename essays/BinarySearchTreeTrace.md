---
layout: essay
type: essay
title: Binary Search Tree Trace
date: 2016-08-26
labels:
  - Software Engineering
  - Learning
---

Binary Search Tree Trace
Joe Palma
When a tree is sorted in a desired order it is referred to as balanced. The runtime of all operations on a tree that is balanced is always Big O(logn). This is because the tree is operated on recursively so if it has any n nodes it is going to take less than n time (logn) to traverse to the right node to operate on. The runtime of a tree is directly proportional to how balanced it is. The more unbalanced the tree is the runtime is more proportional to O(n), the more balanced the tree is its runtime is more proportional to O(logn). Each operation preformed on the tree has an effect on its balance. As you add and remove elements the tree will get more unbalanced. 
When constructing a new Binary Search Tree the first step is to add elements. To add n elements to a sorted tree in the best case (when the elements are already sorted) the runtime of adding them recursively would be O(logn). In the worst case (elements are unsorted) the runtime of adding them recursively would be more proportional to O(n2). This is because every time you add an element out of order you maintain a runtime of O(logn) for n unsorted elements, so the complexity of adding any n elements is O(nlogn).
In this assignment we used the inorder() method on the tree to return a list of the values in the tree in order. In the best case (the tree is sorted) this would require a runtime that is more proportional to O(logn). In the worst case (the tree is unsorted) this would require a runtime that is more proportional to O(n). 
Generally, in a balanced tree the runtime of an operation will be more proportional to O(h) where h is the height. In an unbalanced tree the runtime of an operation will be more proportional to O(n) where n is the number of nodes.
Using trees to hold data can be very efficient when applied correctly, using them will cut down on the runtime of programs because you can skip over large sets of data when traversing them.
