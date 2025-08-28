# RUDRA-recruitment-code
SOLUTION
Understanding(what I understood of the problem):-

* To decode the GPS position of the rover from the datesheet and that would be the starting position of the rover for this code.
* I have to write a path planning algorithm code for the rover to start from the decoded GPS position to the end goal given, with precise directions with respect to  direction, time and wheel parameters.

Thought Process(what direction I would approach to code accordig to):-
* First I would extract information from the datesheet like the wheel parameters, longitude, latitude,height, time, velocity and the direction which it's heading to with the nav pvt message fromt the datesheet.
* Then I will convert the coordinates of the rover to actual position and place(ENU).
* Using graph I would simplify the position coordinates and distance from the end point.
* Generating motion commands like rotate in static motion, move forward, turn specific angles at what distance and coordinate.
* Also generate a code to keep track of total distance travelled, total time taken, and total angular rotation. 
