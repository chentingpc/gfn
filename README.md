Graph Feature Networks (GFN)
--------------------------------------------------------------------------------

## Introduction

This is the implementation for Graph Feature Network (GFN), a simple lightweight neural set function with graph augmented features. It augments nodes with graph structural and propagated features, and then defines the function directly on a set of nodes. See our paper for more details.

## Requirements

* *[pytorch_geometric](https://github.com/rusty1s/pytorch_geometric/releases)*

This code is developed under version 1.1.0. So if it doesn't work for your pytorch_geometric, you may want to install the right version.


## Run the experiments

Replace the exp below with whichever you want to run, see all exps in main.py.
```
python main --exp benchmark
```
