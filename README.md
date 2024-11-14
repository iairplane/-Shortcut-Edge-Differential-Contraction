Shortcut-Edge Differential Contraction (SEDC)
Overview
This repository implements the Shortcut-Edge Differential Contraction (SEDC) algorithm, a method designed to optimize node contraction in graph-based structures. The primary criterion for node contraction is the edge difference, which is defined as the difference between the number of shortcuts added during node contraction and the sum of the node's original in-degree and out-degree.
The algorithm employs a top-down approach to minimize the increase in out-degree during contraction, effectively controlling the expansion scale. This method is particularly useful in graph optimization, where minimizing edge expansion and preserving the graph's core structure are crucial.
Key Features
Edge Difference Criterion: Node contraction is based on the "edge difference," defined as the number of shortcuts added minus the sum of the original in-degree and out-degree of the node.
Top-Down Approach: The algorithm uses a top-down strategy to control and minimize out-degree expansion.
Efficient Graph Contraction: The algorithm is designed to perform node contractions efficiently while maintaining key graph properties.
Algorithm Description
The node contraction process is based on the following steps:
Shortcut-Edge Differential Contraction (SEDC) is applied, where the edge difference criterion is used to determine the nodes to contract.
Edge Difference Calculation: The edge difference is computed by subtracting the sum of the node's original in-degree and out-degree from the number of shortcuts added during the contraction.
Top-Down Strategy: The top-down approach is employed to minimize the increase in out-degree during the contraction process, ensuring that the graph’s structure remains as close to the original as possible while still benefiting from the contraction.
The detailed node contraction procedure is presented in the Algorithm~\ref{contraction} section of the accompanying paper or code documentation.
