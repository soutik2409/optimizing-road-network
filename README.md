# optimizing-road-network
A city has a poor street management system where accidents and traffic jams occur frequently. The city has n intersections which are interconnected by m bidirectional streets. The mayor of the city decides to make every street unidirectional to simplify the road network system so that traffic jams and accidents can be reduced. Our job is to find the direction of each road and also find the number of bridges (or the number of paths which have to be kept bidirectional).
Note that initially, all the intersections are interconnected. And after assigning directions to the paths, they should remain connected.

INPUT:
The first line of the standard input contains two integers n and m (2 ≤ n ≤ 1 000 000, 1 ≤ m ≤ 1 000 000), separated by a single space, which specify the number of intersections and of streets in the city respectively. The intersections are numbered with integers from 1 to n. The m lines that follow describe the street network; the i-th such line holds two integers ai , bi (1 ≤ ai , bi ≤ n, ai 6= bi), separated by a single space, which indicate that the i-th street directly links the intersections no. ai and bi . There can be more than one street directly linking any pair of intersections. 

OUTPUT:
In the output, the edges will be directed by an arrow sign pointing from node to other. In case of a bridge, a bidirectional arrow will be given. Also, the number of bridges in the graph is displayed.


