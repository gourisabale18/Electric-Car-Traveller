# Project-1:- Electric-Car-Traveller

## Group members name and their CSUF Email id:-
1. Kunal Chhatrapati(kunalchhatrapati@csu.fullerton.edu)
2. Vallari Rajurkar(vallarirajurkar@csu.fullerton.edu)
3. Gouri Sabale(gourisabale123@csu.fullerton.edu)

## Summary of Report
The problem of Electric Car Traveler is the main emphasis of the report. Therefore, the goal of this task is to determine the smallest number of stops needed to go to the target city. The current city must be used as the source city, the destination city as the next city, and initializeleftCapacity to the entire capacity at the start city in order to determine the minimum number of trips. The start city will then be added to the list of stop stations, and we will repeat this process until we reach the final city. Recalculating the left capacity in that case would include determining if it is greater than or equal to the distance to be traveled.We must return to the previous state if leftCapacity is less than 0, fill it to full, and then add the current city to the list of stop stations. We can move to the next city and add the left capacity with the following distance if we have extra capacity. At the end, we will return the list of stations and add Destination city to the stop stations list.



