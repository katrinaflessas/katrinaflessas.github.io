---
layout: project
type: project
image: img/shape-calculator/shapecalculator.png
title: "Shape Calculator"
date: 2026
published: true
labels:
  - C++
  - Object-Oriented Programming
  - Inheritance
  - Polymorphism
summary: "I developed a C++ program that uses inheritance and polymorphism to calculate the area, surface area, and volume of different two- and three-dimensional shapes."
---

I created this Shape Calculator as a class project for ICS 212 at the University of Hawaiʻi at Mānoa. The program presents a menu that allows the user to select from several shapes, including a circle, sphere, cylinder, square, cube, triangle, and tetrahedron. After the user enters the required dimensions, the program calculates and displays the appropriate area, surface area, or volume.

I used a base Shape class to define the behaviors shared by the different shapes. The individual shape classes inherit from either the Shape class or another related class. For example, Sphere and Cylinder inherit from Circle, while Cube inherits from Square. The program also uses virtual functions and polymorphism so it can call the correct calculation and output methods based on the shape selected by the user.

This project helped reinforce my understanding of classes, inheritance, virtual functions, and polymorphism in C++. It also gave me experience organizing related objects into a class hierarchy and using user input to control a program’s behavior. I used AI assistance to help structure parts of the implementation, troubleshoot errors, and better understand how the classes and polymorphic methods worked together.
