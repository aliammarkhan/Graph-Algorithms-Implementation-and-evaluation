# Graph-Algorithms-Implementation-and-evaluation

This project implements graph algorithms and on the basis of the given set of inputs, display and then generate the results. Python has been used for the implementation of the given algorithms

# Algorithms used:

The algorithms implemented are as follows:
1. Prim’s Algorithm for minimum spanning tree
2. Kruskal’s Algorithm for minimum spanning tree
3. Dijiskstra Algorithm for single source shortest path
4. Bellman Ford Algorithm for single source shortest path
5. Floyed Warshall for all pair shortest path
6. Clustering Coefficient in Graph theory

The program will initiate with the main.py file,which will prompt a very basic GUI
and ask the user to select the input file , on selection it will prompt the graph
according to the co-ordinates provided in the input file. After , it will ask for the
algorithm that the user wants to implement and on selection will show the final graph
and the result after running the algorithm on the inputs. The user can then select
another input file or exit the program.

# Setup
The following considerations have been made while
making this program:
1. The program will run on the input files provided with the project and any other
files based on the same format
2. The algorithms used for implementing Prim’s , Kruskal , Dijikstra, Bellman
Ford are all based on the greedy approach while Floyd Warshall is
implemented using the principles of Dynamic Programming. No particular
algorithmic technique is considered while implementing Clustering
Coefficient.
3. The implementation of the single source shortest path algorithms is done for
the directed graphs but it can also work for the undirected graphs by making
minor changes in the code . All those changes have been commented out.
4. The data structures used in this project are graphs and lists. Although
dictionaries has also been used but their usage is very minor and just for the
sake of showing output.
5. Python Libraries used in the project are

   • networkx(for strong graphs and processing)

    • matplotlib(for displaying graphs)

    • tkinter (for GUI)

    • statistics

Refer to the docs of the above libraries for installing.

# Results
The following are the results obtained by running the algorithms on the given set of
inpits. Prim’s , Kruskal and cluster coefficient results are based on the undirected
graph while the rest are for the directed. All weights are divided by 10000000

![1](https://user-images.githubusercontent.com/50051546/91600526-88005e80-e981-11ea-9eea-e2f8ca0b20e6.png)

Since there are no outgoing edges from the source vertex (1) in Dijikstra and
Bellmanford so the distance from source to all other vertices is inf . The Floyd
Warshall cost is shown as the total distance of all the pairs plus inf ( the distance of
the unreachable pairs).

Dijkstra and Bellman ford for undirected graph



# References:
1. Introduction to the Design & Analysis of Algorithms by Anany
Levitin
2. https://www.geeksforgeeks.org/fundamentals-of-algorithms/
3. https://stackoverflow.com/


