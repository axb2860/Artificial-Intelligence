Ashwin Babu1001392860
CSE 4308-001
Assignment 1

Programming Language: Java

Implemented the Graph search using Uniform Cost Search Algorithm to get the optimal route available as per the given routes in the file. The functions used are as follows:

In class find_route the function Adding_children is used to add the cities and distance information to the array list children if either of the city is source or destination, the function get_distance returns the distance between two cities if either city is a source or destination in the route_found array list, the function print_route prints the path by backtracking the parent node from which we found the optimal path to the destination. In main method i am taking the command line input and calling the various functions.

In class file it is used to traverse through the file of routes and extract the name of the cities to check if it is a source_city or destination_city.

In class node there are various function to get the information of the city example its cost depth its parent node from which it was explored.

Commnads to run on omega server:

 Paste all the files in the same folder then open omega and type \'93javac find_route.java\'94\
Next step, type \'93java find_route input1.txt source destination\'94 (Use any destination and source city to get optimal path)
