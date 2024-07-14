Euclidean Distance Calculator

This Python program calculates the Euclidean distances between points in a 2D space and finds the shortest distance.

#What is Euclidean Distance?

Euclidean distance is the "ordinary" straight-line distance between two points in Euclidean space. In a 2D space, the distance is calculated using the formula:

d = sqrt{(x₂ - x₁)² + (y₂ - y₁)²}


Program Functionality

#Defining Points:

A list named points is created, containing tuples that represent points in 2D space. For example, the point (x, y) is represented as a tuple (x, y).

#Writing a Function for Euclidean Distance:

A function named euclideanDistance is defined. This function takes two tuples (each representing a point) and returns the Euclidean distance between these two points.

#Calculating Distances:

Using a loop, the Euclidean distance between every pair of points in the points list is calculated. These distances are stored in another list called distances.

#Finding the Minimum Distance:

The minimum distance from the distances list is found and printed.
