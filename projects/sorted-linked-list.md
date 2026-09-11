---
layout: project
type: project
image: img/SortedLinkedList.png
title: "Sorted Linked List"
date: 2025
published: true
labels:
  - Java
  - Data Structures
  - Linked Lists
summary: "I implemented a generic sorted linked list in Java that maintains the correct order as elements are added and removed."
---



I created this project for ICS 211 at the University of Hawaiʻi at Mānoa. The program implements a sorted linked list in Java that can store different types of comparable data, including integers and strings. Unlike a regular list, it automatically places each new element in the correct position instead of simply adding it to the end.

I created a custom node class to store each element and connect it to the next node in the list. The program includes methods for adding, retrieving, locating, and removing elements. I also implemented an interface that defines the list’s required operations and used Java generics so the same data structure can work with multiple data types.

To test the implementation, I created lists of integers and strings and verified that the elements remained sorted after additions and removals. The tests also checked the list’s size, element locations, and error handling. This project gave me experience implementing a data structure without relying on Java’s built-in linked-list class and reinforced my understanding of nodes, references, interfaces, and generics. I used AI assistance to help structure parts of the implementation, troubleshoot errors, and better understand how the linked-list operations worked.
