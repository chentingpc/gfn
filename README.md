Graph Feature Networks (GFN)
================================================================================

This is the implementation of GFN used in paper "Dissecting Graph Neural Networks on Graph Classification". GFN is a simple lightweight neural set function with graph augmented features. It augments nodes with graph structural and propagated features, and then defines the function directly on a set of nodes. See [our paper](https://arxiv.org/abs/1905.04579)  for more details.

## Requirements

* *[pytorch_geometric](https://github.com/rusty1s/pytorch_geometric/releases)*

This code was developed under version 1.1.0. So if it doesn't work for your pytorch_geometric, you may want to install the right version.


## Run the experiments

Replace the `benchmark` experiment below with whichever you want to run, see all exps in main.py.
```
python main --exp benchmark
```

## Cite

Please cite [our paper](https://arxiv.org/abs/1905.04579) if you find it helpful in your own work:

```
@article{gfn2019,
  title={Dissecting Graph Neural Networks on Graph Classification},
  author={Ting Chen, Song Bian, Yizhou Sun}
  journal={CoRR},
  volume={abs/1905.04579},
  year={2019},
}
```

