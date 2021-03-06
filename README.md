# Directional Graph Networks

Implementation of Directional Graph Networks in PyTorch and DGL.

![method](realworld_benchmark/images/full-method.png)

## Overview

We provide the implementation of the Directional Graph Networks (DGN) in PyTorch and DGL frameworks, along with scripts for running real-world benchmarks. The repository is organised as follows:

- `models` contains:
  - `pytorch` contains the various GNN models implemented in PyTorch: the implementation of the aggregators, the scalers, the DGN layer and the directional aggregation matrix (`eigen_agg`).
  - `dgl` contains the DGN model implemented via the [DGL library](https://www.dgl.ai/): aggregators, scalers, and DGN layer.
  - `layers.py` contains general NN layers used by the various models
- `realworld_benchmark` contains various scripts from [Benchmarking GNNs](https://github.com/graphdeeplearning/benchmarking-gnns) 
and [Open Graph Benchmark](https://ogb.stanford.edu/) to download the real-world benchmarks and train the DGN on them. 
In `realworld_benchmark/README.md` we provide instructions for runnning the experiments.

## License
MIT
