# Distance-Vector-Routing

Implemented a distributed and asynchronous distance vector routing protocol using Python.
Coded the logic for a router node to calculate shortest paths using the Bellman-Ford algorithm.
Incorporated the Poisoned Reverse technique to prevent routing loops in dynamic network topologies.

Start the simulator by typing (with default configuration):
          % python3 RouterSimulator.py

To change the values (disabling link cost change, poison reverse, number of nodes):
          % python3 RouterSimulator -c false -p false -n 4
