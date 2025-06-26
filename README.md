# Social Network Analysis and Influence Maximization

## Overview

This project focuses on analyzing social networks using graph theory and implementing influence maximization techniques. The primary goals are to:

1. **Analyze Network Properties**: Compute centrality measures, PageRank, and community structures.
2. **Influence Maximization**: Compare seed selection strategies using the Independent Cascade (IC) model and the Greedy algorithm.

Social Network Course by Dr. Maryam Hosseini
## Features

- **Network Analysis**:
  - Degree, Closeness, Betweenness, and Eigenvector Centrality.
  - PageRank and Radius/Diameter calculations.
  - Community detection and visualization.
- **Influence Maximization**:
  - Independent Cascade (IC) model simulation.
  - Greedy algorithm for optimal seed selection.
  - Comparative analysis of seed selection strategies.

## Installation

To run this project, ensure you have the following Python libraries installed:

```bash
pip install networkx matplotlib pandas seaborn
```

## Usage

1. **Network Analysis**:
   - Load network datasets (`football.edges`, `dolphins.edges`).
   - Compute and visualize centrality measures and community structures.

2. **Influence Maximization**:
   - Simulate the Independent Cascade model for different seed sets.
   - Implement the Greedy algorithm for optimal seed selection.
   - Compare the effectiveness of various seed selection strategies.

## Results

- **Network Visualization**: Graphs with nodes colored by community and edges styled by intra/inter-community connections.
- **Influence Spreading**: Comparative analysis of seed selection methods (Degree, Closeness, Betweenness, PageRank, Eigenvector, Greedy) based on average spread.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Datasets**: Football and Dolphins networks from [Network Repository](https://networkrepository.com/).
- **Libraries**: NetworkX, Matplotlib, Pandas, Seaborn.

## Contact

For any inquiries, please contact **Iman Khalilorahmani** at [imankhtech@gmail.com](mailto:imankhtech@gmail.com).

---
