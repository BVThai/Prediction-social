# Link Prediction and Social Network Analysis

## Overview
This project analyzes a social network graph, computes metrics for nodes and edges, and implements link prediction algorithms. Metrics include custom values (`True`, `Indeterminacy`, `Falsity`) and traditional algorithms like Common Neighbors and Jaccard Index.

## Dataset
- **Vertex Data (`Vertex.csv`)**: Node attributes (e.g., friends, engagement).
- **Edge Data (`Edge.csv`)**: Relationships with mutual friend weights.
- **Predicted Edges (`Predict_edge.csv`)**: Potential edges with distance metrics.

## Installation
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install pandas networkx matplotlib tabulate
3. Add the following files to the project directory: Vertex.csv, Edge.csv, and Predict_edge.csv to the project directory.
## Workflow
1. **Graph Construction**: Build and visualize the social network.
2. **Node Metrics**: Calculate True Value, Indeterminacy, and Falsity.
3. **Edge Metrics**: Compute metrics like normalized True Value.
4. **Location-Based Metrics**: Analyze distances for prediction.
5. **Link Prediction**: Implement algorithms (e.g., Jaccard, Adamic-Adar).
6. **Comparison**: Normalize scores and visualize results.
## Algorithms
- **Custom Metrics**: True Value, Indeterminacy, Falsity.
- **Traditional Methods**: Common Neighbors, Jaccard Index, Adamic-Adar, etc.
## Results
- Visualized graph with node/edge metrics.
- Compared link prediction scores across methods.
## References
Mahapatra, R., Samanta, S., Pal, M., & Xin, Q. (2020). Link Prediction in Social Networks by Neutrosophic Graph. International Journal of Computational Intelligence Systems, 13(1), 1699–1713. DOI:10.2991/ijcis.d.201015.002



