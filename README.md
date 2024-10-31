# Circular Queue Implementation in C++

This repository contains a simple implementation of a circular queue using C++. The circular queue is a data structure that uses a fixed-size array to represent a queue in a circular fashion. It allows for efficient use of memory and enables the reuse of space when elements are dequeued.

## Features

- **Enqueue**: Add an element to the rear of the queue.
- **Dequeue**: Remove an element from the front of the queue.
- **Peek**: View the front element of the queue without removing it.
- **Check Full**: Determine if the queue is full.
- **Check Empty**: Determine if the queue is empty.
- **Display**: Print all elements in the queue.

## Getting Started

To run this program, ensure you have a C++ compiler installed (e.g., g++, clang++). You can compile and run the program using the following commands:

```bash
g++ -o circular_queue circular_queue.cpp
./circular_queue
Code Explanation
The main components of the Cirqueue class include:

Member Variables:

a[10]: Array to hold the elements of the queue.
n: Maximum number of elements the queue can hold (fixed at 5).
front: Index of the front element.
rear: Index of the rear element.
Member Functions:

isfull(): Checks if the queue is full.
isempty(): Checks if the queue is empty.
enqueue(): Adds an element to the queue.
dequeue(): Removes an element from the queue.
peek(): Displays the front element.
display(): Displays all elements in the queue.
