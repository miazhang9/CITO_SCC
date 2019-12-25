# CITO_SCC

Data for CITO with Similar Class Combination.

To show the difference between the original program and the reduced program more intuitively, 
Object Relation Diagrams (ORDs) are provided for each program before and after combining similar classes.
The value in each node indicates the class number, and the directed edge represents the dependency between two classes. 
Programs daisy and deos are not included, because deos does not contain any similar classes defined by our properties, and the number of cycles in daisy is unchanged.

In order to simplify the problem, we only provide ORDs for strongly connected components that contain similar classes. Therefore, the number of nodes and edges in each program are not the total number of classes and class dependencies.

In each program, it contains seven files.

XX_Edges_ICD.csv: All edges in the ORD constructed for the program after combining similar classes based on identical class dependence. Each edge is from source node to the target node.

XX_Edges_Original.csv: All edges in the ORD constructed for the program without similar class combination.

XX_Nodes_ICD.csv: All nodes in the ORD constructed for the program after combining similar classes based on identical class dependence. Each value is the class number.

XX_Nodes_Original.csv: All nodes in the ORD constructed for the program without similar class combination.

XX_ORD_ICD.pdf: ORD constructed for the program after combining similar classes based on identical class dependence.

XX_ORD_Original.pdf: ORD constructed for the program without similar class combination.

XX_ICD.txt: Similar classes that are identified by identical class dependence.



