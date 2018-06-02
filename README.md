# visualize SCC (strong connected components) using d3 force directed graph

Code-SCC.cpp uses tarjan algorithm to output SCC and edges connecting them to res.txt;

There may be many edges connecting two components, repeat.py outputs clean.txt leaving only one edge so in visualization edges do not overlap;

clean.txt → mis.json;

index.html uses force simulation in d3. Giving edges repulsive force in simulation to separate components and make sure edges do not cross each other. Radius of metanode propotional to SCC size. 
