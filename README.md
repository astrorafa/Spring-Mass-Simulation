# Spring-Mass-Simulation

This repository has code for simulating the srping mass physical system. The system is governed by a second-order differential equation that can be broken down into a set of first-order two differential equations. To solve the system numerically, I used Runge-Kutta 4 that takes a tuple of values (current position and velocity) and returns the next position and velocity of the bob. RK4 is a forth-order method that is the standard numerical method for solving differential equations when one uses a built-in solver. One can change the parameters of the system to see how it is influenced by simulation values and initial conditons.
