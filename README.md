# Network Analysis Project

This project focuses on analysing the Starlink network and their connections to cities.

## Project Structure
- **`analysis.ipynb`**: Jupyter Notebook containing the analysis of precreated networks. Simply execute the cells to view the results.
- **`networks/`**: Directory containing all the precreated networks:
  - **`bipartite.graphml`**: Bipartite graph connecting satellites to cities.
  - **`satellite.graphml`**: Satellite-only network derived from the bipartite graph.
  - **`snapshot.graphml`**: Snapshot of the satellite network at specific time points.

## Precomputed Data

To ensure reproducibility and reduce variability:
- Networks have also been precreated and loaded into this repository.
- The Louvain communities have been precomputed as the output is not deterministic.

## How to Run

### Generating Networks

The networks have already been precreated and saved in the networks directory.

### Analysing Networks

1. Open `analysis.ipynb`.
2. Run each cell sequentially to compute metrics and visualise results.

## Dependencies

Ensure you have the following Python packages installed:
- `networkx`
- `numpy`
- `seaborn`
- `matplotlib`
- `scipy`
- `powerlaw`
- `basemap`
- `geopy`
