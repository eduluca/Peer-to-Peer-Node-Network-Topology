# Peer-to-Peer Node Network Topology

## Overview:
This project involves network simulation techniques and provides insights into the dynamics of communication networks under different topologies and conditions using Python. The project explores the behavior of nodes and their interactions in two different network topologies: a Ring topology and a Spectacles topology.

## Key Components:

Node Class: Defines the properties and behaviors of individual nodes in the network, including their RGB values, XYZ and Lab transformations, distance calculations, and neighbor management.

Topology Generation: The program generates either a Ring topology or a Spectacles topology based on user input. In the Spectacles topology, nodes are arranged in two circles and a semicircle.

Communication Simulation: Nodes communicate with their neighbors over multiple cycles, exchanging information and updating their neighbor lists based on certain criteria. Two communication options are provided, each affecting how nodes update their neighbor lists.

Visualization: The program visualizes the network topology and node connections using matplotlib. It saves snapshots of the network at different cycles for analysis.

Analysis:
Effect of k Value: The assignment explores how the choice of the number of neighbors (k) influences the behavior and connectivity of nodes in the Spectacles topology.

Connectedness: By varying the value of k, the assignment aims to determine the minimum number of neighbors required to ensure connectivity among the three components (two circles and a semicircle) of the Spectacles topology after a certain number of cycles.

## Output:
The program outputs visualization snapshots of the network topology at different cycles, along with text files detailing the neighbor lists of each node.

Additionally, it calculates and prints the total distance between nodes at each cycle, providing insights into the overall behavior of the network.
