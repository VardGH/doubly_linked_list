# doubly_linked_list Implementation in C++

This project provides a C++ implementation of a doubly linked list data structure along with various operations like insertion, deletion, sorting, and more.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Example](#example)

## Introduction
A doubly linked list is a fundamental data structure that consists of nodes, each containing data and pointers to both the previous and next nodes in the sequence. This implementation provides a dynamic and memory-efficient way to manage collections of elements.

## Features
- Insert elements at the beginning, end, or at specific positions.
- Remove elements from the beginning, end, or at specific positions.
- Clear the entire list.
- Check if the list is empty.
- Get the size of the list.
- Reverse the list in-place.
- Sort the list using the merge sort algorithm.
- *Add more features as needed.*

## Usage
You can use this implementation by including the `doubly_linked_list.hpp` and `node.hpp` header files in your project. The `DoublyLinkedList` class provides a comprehensive set of methods to interact with the doubly linked list data structure.

### Example
Here's a simple example of how to use the Doubly Linked List implementation:

```cpp
#include "doubly_linked_list.hpp"

int main() {
    DoublyLinkedList<int> list;
    list.push_back(42);
    list.push_back(17);
    list.push_front(31);

    list.print_list(); // Output: 31 42 17

    list.pop_back();
    list.pop_front();
    list.print_list(); // Output: 42

    return 0;
}
```