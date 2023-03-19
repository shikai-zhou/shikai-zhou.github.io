---
layout: post
title: Data Structures: Array and Linked list
subtitle: 
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [coding, data-structures, algorithms]
---
# Data Structures: Arrays and linked lists
When delving into world of data structures, one of the first data structures taught are arrays and linked lists.
Let's look at the main differences between them.

## Memory layout
### Reading and writing
In an array, elements are contiguous in memory. This means that access time is constant time O(1).

In a linked list, elements are often not contiguous in memory, which means that to access memory requires the program to loop through the entire list to retrieve the value of index i. This results in slower access times of O(n).
## Insertion and deletion
To insert a new element at the end of an array, it takes O(1). The same applies to a linked list if we keep track of the last node.
To insert a new element at a specified index i, the complexity is O(n) for an array as we have to shift all the elements after the index i to index i+1. For a linked_list, we take O(1) time, if we do not count the time taken to traverse the linked list.
new.prev = &prev
new.next = prev.next
prev.next = &new
## Resizing

This is where linked list have an advantage, since linked lists are usually dynamically sized, resizing a linked list is cost-free while arrays are statically sized, hence changing the size of an array would require a costly reallocation of memory.

## Space 

Although both data structures take up O(n) space, a ll requires more auxillary space for book-keeping, especially for doubly-linked lists, which keeps track of both previous and next nodes. 

## Dynamic Array
Many languages use dynamic arrays to achieve the best of both worlds such as C++ vectors, Java ArrayList and python lists. Dynamic array achieve both fast access time and fast resizing amortized. 

Watch this [video](https://www.youtube.com/watch?v=5AllG-i_yto) to learn more about designing your own dynamic array.
