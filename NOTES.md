ADDITIONAL METHODS:
    File name:

# Description:
0. Was left as exercise -> sudo code provided.
    1. GraphPackage directory.
        a) With exception to the DirectedGraph.java file, most code is from the books website. In places where needed, I used the java.util libary instead of using the book's "provided" library as in roughly most cases I would have had to write the code. 
        b) The DirectedGraph.java: pg 863
            a) getBreadthFirstTraversal() code provide from book
            b) getDepthFirstTraversal() was left as exercise.
            c) getShortestPath() code proivded from book.
            d) getCheapestPath() was left as exercise.
    2. Finish description.


## NOTES:
1. ### Using iterators to encapsulate data.
    * The iterator will visit a vertex neighbors in the same 
    order the neighbors were connected/added to the graph this
    removes the need for methods like frontVertex.getEdgeList
    try to do the same for your other projects. Limiting access to stuff.
2. ### Objects ambiguous problems.
    1. When you run into ambiguous problems with objects i.e the correct objects are not modified correctly, try printing to file or output the hashcodes of the stored object and the object being modified.
        1. **Verbose:** 
            * nextNeighbor = neighbors.next() seemed to return a copy of the next vertex and not the actual vertex stored in the graph. That's why I had to get the actual vertex in the graph. The book uses nextNeighbor = neighbors.next().

*** IMPORTANT ***
1. ## A. Read chapter 18 pg 526-535 on inherintace.

*** Needs To Be Done ***
1. Make it easier when choosing which algorithm to run.