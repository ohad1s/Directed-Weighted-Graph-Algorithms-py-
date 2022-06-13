# Directed Weighted Graph Algorithms
**About This Project**

In this project we implmented a directed weighted graph and graph algorithms. In addition, we created a GUI that can load grpahs json file and show them.

**What is Directed Weighted Graph?**

A Directed Weighted Graph is a graph in which the edges that connect the vertices has direction. For example: lets say vertex 1 is connected to vertex 3, than it is possible to travel from vertex 1 to vertex 3 but not the other way aroud unless the is a different edge in the graph that is connecting vertex 3 to vertex 1.

In addition, each edge has a weight, which set the "cost" of traveling along the edge, meaning some times it can be faster to go from one vertex to second vertex through a third vertex even if there is a direct edge from the first vertex to the second vertex. For Example: If there is an edge between vertex 1 and vertex 3 that has a weight of 3, and edges from vertex 1 to 2 and from 2 to 3 that has a weight of 1 each, it is better to get from vertex 1 to 3 through vertex 2.

**Algorithms That Are Implemented:**

Is the Graph Strongly Connected - Checking if the graph is strongly connected using Breadth-first search on the graph, than running Breadth-first search on the inverted graph.

Shortest Path between two vertices - Finding the path and distance using Dijkstra's algorithm.

Finding the Graph Center - Finding the vertex in the graph, that has the minimal distance to the farthest vertex using Dijkstra's algorithm.

Finding Shortest Path For List of Vertices - Using a greedy algorithm and Dijkstra's algorithm in order to find the shortest path that goes through all the vertices in the list.

**How To Run The Program:**
We have two executable files: main.py and drawGraph.py

main.py is a file that has set graphs that it is loading, running algorithms on them and print the results.

In order to run main.py, simply enter the src directory, open cmd through src path and run the following command: python3 main.py

drawGraph.py is a file that take a graph json file as an argument, and print it to the screen. json files of graphs are located in the data directroy.

In order to run drawGraph.py, enter the src directory, open cmd through src path and run the following command: python3 drawGraph.py <grap_json_file>

For both files, the following window should pop up with the relevant graph. Please notice that with the main.py executable, four graph will open one after the other.

![image](https://user-images.githubusercontent.com/92723105/173436463-a1c1e83b-c060-4fb4-8ee6-1d0ad8029df4.png)

**Project UML:**

![image](https://user-images.githubusercontent.com/92723105/173436531-431ebdad-65d8-40c9-9f52-88699bdb344a.png)


**Comparison of runtimes with the Java Project:**

Before I did this project,I have done it in Java.

You can see the Java project here- https://github.com/ohad1s/Ex2_OOP.git

below is the runtime comparison between the 2 projects:

I compared the projects between 4 different graphs with 4 different algorithms (Load, Save, Center, TSP)

(TSP runtime measured on all the vertices of the graph)

(Computer specifications: Lenovo V14-IIL, Intel Core i5-1035G, Windows 10 Pro 64 16GB memory card)

Graph G1:

![image](https://user-images.githubusercontent.com/92723105/173436182-f2c898e2-5c27-4e38-8961-43db6bba5c97.png)
![image](https://user-images.githubusercontent.com/92723105/173436202-c41900d6-6b65-4a30-b7bc-b948daedaaec.png)


Graph G2:

![image](https://user-images.githubusercontent.com/92723105/173436227-2687b36c-1488-496b-b4c5-786a4404ef6b.png)
![image](https://user-images.githubusercontent.com/92723105/173436252-7840dbdd-1e27-46eb-a00b-94f4fb84af2a.png)


Graph G3:

![image](https://user-images.githubusercontent.com/92723105/173436296-752127b0-6583-4628-a77a-115260aed4b0.png)
![image](https://user-images.githubusercontent.com/92723105/173436308-bb1d770b-795b-4b84-9df8-e25feb129261.png)


Graph 1000Nodes:

![image](https://user-images.githubusercontent.com/92723105/173436323-15eb010a-a253-4363-8a60-790c204833fd.png)
![image](https://user-images.githubusercontent.com/92723105/173436338-76b0d4c5-7677-4d6f-9693-c09177c2a3b6.png)


