# The shortest path


The problem consists of determining the intermediate stations for the shortest path. 

There are four zones in a traffic system: Z1, Z2, Z3, and Z4. Zone Z1 only includes station X, and zone Z4 only includes station Y. Zone Z2 includes stations U1, U2, ..., Um (m is a positive integer), and zone Z3 includes stations V1, V2, ..., Vn (n is a positive integer).
There are direct roads between station X and all stations in zone Z2. Zones Z2 and Z3 are well connected to each other: there is a direct road between any station in one zone and an arbitrary station in the other zone. There is also a direct road between any station in zone Z3 and station Y. There are no other roads between given stations.

For any arbitrary integer i, 1 ≤ i ≤ m, the length of the road between station X and station Ui is ai.

For any arbitrary integer i, 1 ≤ i ≤ m, and for any arbitrary integer j, 1 ≤ j ≤ n, the length of the road between station Ui and station Vj is bij.

For any arbitrary integer j, 1 ≤ j ≤ n, the length of the road between station Vj and station Y is cj.

A road between stations X and Y passes through a station in zone Z2 and a station in zone Z3. 

Intermediate stations in each of zones Z2 and Z3 should be chosen so that the road between stations X and Y is as short as possible.

It may happen that there are several roads that have the shortest length. In that case, intermediate stations on one of these roads should be determined.
