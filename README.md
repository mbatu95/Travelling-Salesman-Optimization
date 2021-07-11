# Travelling-Salesman-Optimization
Genetic algorithm and Simulater Annealing Method for Travelling Salesman Problem


Travelling salesman is a problem which asks the following question; how to travel on a route of a given cities with given distances to each other. As city numbers increases solution time and solution clearness increases. In this project Turkey cities were used as cities that the salesman will travel. Since there are 81 cities on Turkish map, it can be said that it is almost impossible to find the best path with brute force. But the optimum value for the best path can be estimated by using algorithms such as genetic algorithm (GA) and simulated annealing(SA)

 Steps of Genetic Algorithm Used in This Project:
Defining coordinates of 81 cities of Turkey to the Python, and storing them as numpy arrays as x and y
Assigning Ankara as the beginning and ending point, also shuffling the path.
Defining distances between the cities to the python as numpy arrays.
Function for drawing path for the salesman
Crossing over process which means the creating new generation paths from older generation paths by adding them each other, subtracting doubled cities and adding missing cities. Also making mutations which means, increasing the diversity of populations by randomly changing two cities on a route
Creating initial population for salesman.
Creating the new generations from older ones by using the functions written before, 
Finally running the code with for loop with number of maximum iterations of 10000, plotting the fitness and path plots and calculating the optimum distance in iteration.


Steps of Simulated Annealing Used in This Project 
Defining coordinates of 81 cities of Turkey to the Python, and storing them as numpy arrays as x and y
Defining Ankara as the beginning point for the salesman
Define the First Temperature and Cooling Speed.
Create a random path.
Create a new path by changing two points of the current path.
Calculate the distance of each path.
Update temperature using equation
Loop until the condition you want is met:
