By Monday, April 27th, I would like to have a working code for the system of equations. Ultimately, this means I will have a working
function that plots the relationships between the two animals in question. I would also like to make a quality docstring for my paper and
figure out how to test it like the step in the reading explained.

The equations:
dx/dt = ax-bxy    and        dy/dt = cxy-dy
will be the functions that I will be using to model my predator vs prey system.
This system of equations shows that the prey reproduces at a rate that is dependent on their population, but are eaten by the predator at a rate proportional to both the predator and prey’s population. a, b, c, and d are constants. 

Outline update for April 27th(HW19):
I have drafted two functions for the project. The first function, pp, is the predator prey function that stores both the predator and prey model(above) into a single parameter, r. 
The next function I have drafted is a solution solving function that plugs the inputted function through a fourth-order runge-kutta method meant for solving a function with two ODEs simultaneously. 
The function outputs a graph relating the two equations simultaneously, showing how they are interrelated over time. There is only one bug at the moment that has to do with which constants I'm choosing at the beginning.
At the moment, I'm unsure of how I am actually able to test this to be correct because it is difficult to solve simultaneous ODEs analytically. I could try to plug it into another software, but I do not know for sure yet.
As for the next steps, I still have to write an introduction to the project. I have to figure out a way to check if my code is working correctly, and I would like to change my plotting to object oriented. Once it works perfectly, I would like to find out which variables are critical and run tests to determine which coefficients keep the two populations thriving.
