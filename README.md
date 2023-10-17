# CPPDS_Constructers_Destructers

# Copy Constructor in C++

This repository contains a C++ program that illustrates the use of copy constructors. In the example, a `Wall` class is defined to represent walls, with attributes for length and height.

## Code Overview

- The `Wall` class has a parameterized constructor to initialize the `length` and `height` of a wall.

- It also defines a copy constructor, which creates a new `Wall` object as a copy of an existing `Wall` object, preserving its `length` and `height` values.

- The `calculateArea` method is used to calculate the area of a wall.

## How It Works

1. Two `Wall` objects, `wall1` and `wall2`, are created.
2. `wall1` is initialized with a length of 10.5 units and a height of 8.6 units.
3. `wall2` is created as a copy of `wall1` using the copy constructor.
4. The areas of both `wall1` and `wall2` are calculated and displayed.

## Example Output


The output shows that both `wall1` and `wall2` have the same area, demonstrating the successful use of the copy constructor.

## How to Run

1. Compile the code using a C++ compiler (e.g., g++):

   ```sh
   g++ -o copy_constructor copy_constructor.cpp

./copy_constructor
