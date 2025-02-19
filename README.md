# Object-Oriented Programming in Dart

This project showcases the concepts of object-oriented programming (OOP) in Dart. It includes various components such as classes, inheritance, interfaces, method overriding, file input, and loops.

## Project Structure

The project consists of the following files:

1. **oop_dart.dart**: This file contains the Dart code that demonstrates various OOP concepts.

2. **data.txt**: This file stores sample data used for initialization and demonstration purposes.

## Code Overview

### Classes and Inheritance

- The project defines classes such as `Mammal`, `Dog`, and `Cat` to demonstrate inheritance. The `Dog` and `Cat` classes inherit from the `Mammal` class.

### Interfaces

- The `Animal` interface is defined with a `makeSound()` method. The `Dog` and `Cat` classes implement this interface by providing their own implementations of the `makeSound()` method.

### Method Overriding

- Both the `Dog` and `Cat` classes override the `makeSound()` method inherited from the `Animal` interface.

### File Input

- The program initializes instances of the `Cat` class with data loaded from the `data.txt` file.

### Loops

- The program demonstrates the use of a loop through the `printNumbers()` method, which prints numbers from 1 to 5.

## Running the Program

To run the program:

1. Make sure you have Dart installed on your system.
2. Clone the repository to your local machine.
3. Navigate to the project directory.
4. Run the `oop_dart.dart` file using the Dart VM.

```bash
dart oop_dart.dart
```
