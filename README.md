# 1991-MCM-B-The-Steiner-Tree-Problem


The cost for a communication line between two stations is proportional to the length of the line. The cost for conventional minimal spanning trees of a set of stations can often be cut by introducing “phantom” stations and then constructing a new Steiner tree. This device allows costs to be cut by up to 13.4% (= 1- sqrt(3/4)). Moreover, a network with n stations never requires more than n-2 points to construct the cheapest Steiner tree. Two simple cases are shown in Figure 1.

For local networks, it often is necessary to use rectilinear or “checker-board” distances, instead of straight Euclidean lines. Distances in this metric are computed as shown in Figure 2.

Suppose you wish to design a minimum costs spanning tree for a local network with 9 stations. Their rectangular coordinates are: a(0,15), b(5,20), c(16,24), d(20,20), e(33,25), f(23,11), g(35,7), h(25,0) i(10,3). You are restricted to using rectilinear lines. Moreover, all “phantom” stations must be located at lattice points (i.e., the coordinates must be integers). The cost for each line is its length.

    Find a minimal cost tree for the network.
    Suppose each stations has a cost w*d^(3/2), where d=degree of the station. If w=1.2, find a minimal cost tree.
    Try to generalize this problem

