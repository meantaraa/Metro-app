# Metro App Overview
The Metro App is a Java application that models a metro system using a graph data structure. The app allows users to interact with the metro map, display stations, find the shortest distance, and calculate the shortest travel time between stations.

# Features
1. Display all stations: Lists all metro stations.
2. Show the metro map: Displays the entire metro map with stations and connections.
3. Shortest distance: Calculates the shortest distance between two stations.
4. Shortest time: Calculates the shortest travel time between two stations.
5. Shortest path (distance-wise): Finds the shortest path based on distance.
6. Shortest path (time-wise): Finds the shortest path based on travel time.
7. Exit: Exits the application.
   
# Installation
1. Clone the repository:https://github.com/meantaraa/metro-app.git
2. Compile the code:javac Graph_M.java
3. Run the application: java Graph_M
   
# Usage
Upon running the application, you will be presented with a menu to choose different actions. Enter the corresponding number to perform an action.
Example
1, List all stations: Choose option 1 to display all the stations in the metro map.
2. Show the metro map: Choose option 2 to display the metro map.
3. Get shortest distance:Choose option 3 and follow the prompts to enter the source and destination stations. The shortest distance will be displayed.
4. Get shortest time: Choose option 4 and follow the prompts to enter the source and destination stations. The shortest travel time will be displayed.

# Code Structure
1. Vertex Class: Represents a station with a list of neighboring stations and their respective distances.
2.Graph_M Class: Contains methods to add/remove stations and edges, display the map, and calculate shortest paths.

# Methods
1. addVertex(String vname): Adds a new station.
2. removeVertex(String vname): Removes an existing station.
3. addEdge(String vname1, String vname2, int value): Adds a connection between two stations.
4. removeEdge(String vname1, String vname2): Removes the connection between two stations.
5. display_Map(): Displays the entire metro map.
6. display_Stations(): Displays all stations in the metro map.
7. hasPath(String vname1, String vname2, HashMap<String, Boolean> processed): Checks if there is a path between two stations.
8. dijkstra(String src, String des, boolean nan): Uses Dijkstra's algorithm to find the shortest path based on distance or time.
9. Get_Minimum_Distance(String src, String dst): Finds the shortest distance between two stations.
10. Get_Minimum_Time(String src, String dst): Finds the shortest travel time between two stations.
11. get_Interchanges(String str): Finds the interchanges in the path.
12. Create_Metro_Map(Graph_M g): Initializes the metro map with predefined stations and connections.
13. printCodelist(): Prints the list of stations with their respective codes.
14. main(String[] args): The main method to run the application.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgements
Java Standard Library for data structures and algorithms.
Metro systems around the world for inspiration.
