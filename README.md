# RUDRA-recruitment-code
RHEA SINGH RA2511026010336

CSE AI/ML(1st year)

SOLUTION- LOGIC BEHIND THE CODE

Understanding (what I understood of the problem):-

AIM:
* To decode the GPS position of the rover from the datasheet and that would be the starting position of the rover for this code.
* I have to write a path planning algorithm code for the rover to start from the decoded GPS position to the end goal given, with precise directions with respect to  direction, time and wheel parameters.

THOUGHT PROCESS (what direction I would approach to code accordig to):-
* TASK 1: First I would extract information from the datasheet like the wheel parameters, longitude, latitude,height, time, velocity and the direction which it's heading to with the nav pvt message from the datasheet.
* Then I will convert the lon-lat coordinates of the rover to actual position and place(ENU) by defining math functions to convert it.
* TASK 2: Using graph I would simplify the position coordinates and distance from the end point.
* TASK 3: Generating motion commands like rotate in static motion, move forward, turn specific angles at what distance and coordinate.
* Also generate a code to keep track of total distance travelled, total time taken, and total angular rotation.
* TASK 4: To write the code and run.

Implementation(How did i think to apply the above thought process):-
* To even start the coding from start position, we need to know its current coordinates and distance from the end point.
* With its current position acquired we can plan the path algorithm accordingly like how much distance to travel before taking and turn or changing direction.
* Simplifying the coordinates is for our own easy understanding.
* Then writing the grid based path algorithm with the gained information for detailed and precise instructions. And keeping track on its total distance, time and angular rotation for any next path planning datasheet.
