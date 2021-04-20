# Networking_for_BigData-Labs_Assignment1
**Part 1:**
1. Use library scripts to generate p-ER random graphs and
r-regular random graph. Let K denote the number of nodes.
2. Write a script to check the connectivity of a given graph.
algebraic method 1 (irreducibility);
algebraic method 2 (eigenvalue of the Laplacian matrix);
breadth-first search algorithm.
3. Compare the complexity as a function of K of the methods
above by plotting curves of a complexity measure vs K.
4. Let pc (G) denote the probability that a graph G is connected.
By running Monte Carlo simulations, estimate pc (G) and
produce two curve plots:
pc (G) vs. p for Erd ̋os-R ́enyi graphs with K = 100.
pc (G) vs. K, for K ≤ 100, for r-regular random graphs with
r = 2 and r = 8.

**Part 2:**
We aim to compare throughput offered by Fat-Tree and Jellyfish
for the same amount of resources.
N = # of servers.
S = # of switches.
L = # of links connecting switches.
n = # number of ports of a switch.
h = mean shortest path lengths for server-to-server paths.

1. Find r (# of switch ports to be connected to other switches
in Jellyfish) as a function of n so that N, S and L are the
same for Jellyfish and Fat-tree.
2 Write the expression of the application-oblivious throughput
bound TH for an all-to-all traffic matrix among servers. The
expression of TH must be a function of h and n only.
3 Using the exact value of h as a function of n for Fat-Tree (you
must calculate it!) and the lower bound of h for r-regular
random graphs (see slides, but be careful with notation) for
Jellyfish, evaluate TH for n = 20, 30, 40, 50, 60.
