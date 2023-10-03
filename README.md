Flappy Bird Game
A simple implementation of the classic Flappy Bird game using Object-Oriented Programming concepts.

Flappy Bird

Table of Contents
Description
Object-Oriented Programming
Features
Installation
Usage
Contributing
License
Acknowledgments
Description
This project is a recreation of the popular Flappy Bird game using C++ and the SFML library. The game follows the original gameplay, where the player controls a bird that must navigate through a series of pipes without colliding.

Object-Oriented Programming
This implementation utilizes Object-Oriented Programming (OOP) principles to organize and structure the code:

Classes:

Bird: Represents the player-controlled bird. It encapsulates properties like position, velocity, and methods for flapping and updating its state.
Pipe: Represents the pipes that the bird must navigate through. It includes methods for updating pipe positions and checking collisions with the bird.
Game: Orchestrates the game loop, handles user input, and manages the game state. It contains instances of Bird and a vector of Pipe objects.
Encapsulation:

Each class encapsulates its properties and behavior, allowing for cleaner code and easier maintenance.
Inheritance:

While not explicitly shown in this example, OOP allows for potential future extensions or variations of the game. For instance, you could derive a SpecialBird class with unique characteristics.
Features
Classic Flappy Bird gameplay with pipes.
Responsive bird controls using keyboard input.
Randomized pipe generation for dynamic gameplay.
