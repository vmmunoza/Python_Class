# Dog Class in Python

This repository provides a simple example demonstrating the concept of classes in Python, focusing on a `Dog` class.

## Overview

In object-oriented programming, a class can be thought of as a blueprint for creating objects (specific instances of the class). The `Dog` class is a basic representation capturing the essence of a dog with attributes like its name and age and methods that provide behaviors such as describing the dog or making it "speak".

## Features

- **Class and Instance Attributes**: The class has a class-level attribute `species` and instance-level attributes `name` and `age`.
  
- **Methods**: There are methods to describe a dog and make it "speak" or produce a sound.
  
- **Object Instantiation**: Demonstrates how to create objects of the `Dog` class.

## Code Example

```python
class Dog:

    # Class attribute
    species = "Canis familiaris"

    # Initializer / Constructor
    def __init__(self, name, age):
        self.name = name  # Instance attribute
        self.age = age    # Instance attribute

    # Method to describe the dog
    def describe(self):
        return f"{self.name} is {self.age} years old"

    # Method for the dog to make a sound
    def speak(self, sound):
        return f"{self.name} says {sound}"

# Create instances of the Dog class
buddy = Dog("Buddy", 9)
milo = Dog("Milo", 5)
```

## Usage

To utilize the class and create dog objects:

```python
# Create a new dog instance
rover = Dog("Rover", 7)

# Access instance attributes and methods
print(rover.describe())  # Output: Rover is 7 years old
print(rover.speak("Bark Bark"))  # Output: Rover says Bark Bark
```

---
