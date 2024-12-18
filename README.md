# ConflictFreeTowTrainRouting

TowTrainRouting is a comprehensive solution for achieving conflict-free tow train routing in just-in-time manufacturing systems. This repository implements a pixel-based layout system to optimize tow train paths while avoiding collisions.

Key Features:
A* Algorithm: Used to calculate the distance matrix between workstations on a pixelated production layout.
Simulated Annealing (SA): Optimizes tow train routes to meet workstation demands efficiently.
Conflict Detection Algorithm (CDA): Detects and resolves conflicts among tow trains, ensuring smooth operation.
Sample Run:
The system demonstrates how conflicts are detected and resolved. For example:

When two tow trains are on a collision course, the algorithm detects the conflict.
In one scenario, the Red Train is held temporarily to allow the other train to pass, resolving the collision safely and efficiently.

https://github.com/user-attachments/assets/f81b0f82-5291-4e66-9570-bb629709d979

