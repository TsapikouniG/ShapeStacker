ShapeStacker Game

 This repository contains the Java implementation of the ShapeStacker game, developed as part of the coursework for the Object-Oriented Programming Techniques course at the University of Ioannina. ShapeStacker is a simple, Tetris-inspired game where players stack various   geometric shapes to score points based on the area of each shape. The goal is to accumulate as many points as possible before running out of shapes or exceeding the stack limit.

Game Overview

 In ShapeStacker, shapes are generated randomly and include squares, triangles, pentagons, and circles, each with a randomly selected size. Players decide whether to keep each shape. Keeping a shape adds it to the stack and awards points based on the shape's area.          Matching the area of the top shape in the stack multiplies the points for that shape. If the new shape matches the type of the top shape in the stack, both shapes are removed, but the player keeps the points. The game ends when the shape generator exhausts its shapes or   the player's stack reaches its size limit.

Implementation Details

  The project consists of several Java classes:
  •	Shape.java: An abstract class representing a generic shape.
  
  •	Square, Triangle, Pentagon, Circle: Concrete classes that extend Shape and implement methods to compute the area and provide the type of the shape.
  
  •	ShapeGenerator.java: Responsible for generating random shapes and managing the order in which they are presented to the player.
  
  •	Player.java: Manages the player's actions, including deciding whether to keep a shape and calculating the score.
  
  •	ShapeGame.java: Contains the main method to run the game, orchestrating the interaction between the player and the shape generator.
  
  
  


