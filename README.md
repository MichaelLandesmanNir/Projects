# Projects
This repository contains projects I developed as part of my academic studies.

1) Overview
This project was developed as part of a seven-part series of assignments during the second semester of my first year at Bar-Ilan University (BIU). Unusually for a game, it was built using a single thread. The project does not rely on Java's built-in GUI components; instead, it employs a custom GUI implementation included in this repository. The game is a version of Arkanoid, developed as part of an Object-Oriented Programming (OOP) course in my undergraduate studies. It features multiple levels with progressively increasing difficulty on a user-friendly platform.

Implementation Details
The game was developed in Java using the IntelliJ IDEA Ultimate IDE, applying several OOP principles:

Polymorphism and inheritance.
Application of fundamental OOP design patterns, such as Observer, Builder, and more.
Use of various generic collections and data structures like linked lists and arraylists.
Implementation of graphical user interface (GUI) components.
Design Patterns Used

Builder Design Pattern
This pattern was applied to construct different game objects in a systematic way, providing flexibility and simplicity in object creation. Builder classes were designed to create objects such as balls, blocks, boundaries, and paddles, which ensures the code remains organized, readable, and easy to maintain.

Strategy Design Pattern
The strategy pattern allowed for varying behaviors for block placement and coloring in the first level of the game. This design enables the creation of diverse levels with distinct characteristics without altering the core game code, enhancing flexibility.

Decorator Design Pattern
Used to extend the functionality of existing Animation objects, this pattern allows for adding features dynamically. The WaitingForKeyPressDecorator class acts as the decorator, enhancing components like PauseScreen and KeyPressStoppableAnimation. The decorator pattern helps keep the codebase clean and maintainable while extending object capabilities.

Observer Design Pattern
The Observer pattern was utilized for handling events triggered by various game objects. Game objects act as observables, while listener classes function as observers. These listeners respond to events, such as removing blocks or balls from the game or updating the score, allowing new listeners to be added without modifying existing game objects, promoting a modular code structure.

