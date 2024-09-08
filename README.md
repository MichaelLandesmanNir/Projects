# Projects
This repository contains projects I developed as part of my academic studies.

1) Overview
The game is a version of Arkanoid, developed as part of an Object-Oriented Programming (OOP) course in my undergraduate studies. It features multiple levels with progressively increasing difficulty on a user-friendly platform.

Implementation Details
The game was developed in Java using the IntelliJ IDEA Ultimate IDE, applying several OOP principles:
Polymorphism and inheritance.
Application of fundamental OOP design patterns, such as Observer, Builder, and more.

Implementation of graphical user interface (GUI) components.
Design Patterns Used

Builder Design Pattern
This pattern was applied to construct different game objects in a systematic way, providing flexibility and simplicity in object creation. Builder classes were designed to create objects such as balls, blocks, boundaries, and paddles, which ensures the code remains organized, readable, and easy to maintain.

Observer Design Pattern
The Observer pattern was utilized for handling events triggered by various game objects. Game objects act as observables, while listener classes function as observers. These listeners respond to events, such as removing blocks or balls from the game or updating the score, allowing new listeners to be added without modifying existing game objects, promoting a modular code structure.

