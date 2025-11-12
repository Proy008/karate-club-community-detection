# Community Detection on Karate Club Graph

A spectral modularity implementation for community detection on Zachary's Karate Club network. This research project demonstrates recursive bipartition algorithms with comprehensive network analysis.

**Course:** DSC212 Graph Theory  
**Institution:** IISER TVM  
**Student:** Probal Roy (IMS24176)  
**Date:** November 2025

## Project Overview

Implementation of Newman's spectral modularity method for community detection, featuring recursive bipartition, network metrics analysis, and visualization of community evolution.

## Key Features

- Modularity matrix construction and spectral optimization
- Recursive bisection with eigenvalue stopping criterion
- 12 iteration graphs showing community evolution
- Network metrics analysis (degree, betweenness, closeness, clustering)
- Node role classification (hubs, bridges, local leaders)
- Performance validation against ground truth

## Mathematical Framework

Modularity matrix:
$$\mathbf{B} = \mathbf{A} - \frac{\mathbf{k}\mathbf{k}^\top}{2m}$$

Modularity optimization:
$$Q = \frac{1}{4m} \mathbf{s}^\top \mathbf{B} \mathbf{s}$$

## Results

- Final Modularity: Q = 0.4188
- Communities Detected: 4
- Accuracy: 94.1%
- Key Nodes: Node 0 (hub), Node 33 (bridge), Node 1 (local leader)

## Requirements

```bash
pip install numpy networkx matplotlib scipy pandas
```

## Usage

```bash
jupyter notebook DSC212_Modularity_KarateClub_Analysis.ipynb
```

Execute all cells to reproduce the complete analysis.

## Project Structure

```
DSC212_Modularity_KarateClub_Analysis.ipynb
README.md
LICENSE
```

## References

1. Newman, M. E. J. (2006). "Modularity and community structure in networks"
2. Zachary, W. W. (1977). "An information flow model for conflict and fission"

## License

MIT License

---

DSC212 Graph Theory Research Project | IISER TVM | November 2025
