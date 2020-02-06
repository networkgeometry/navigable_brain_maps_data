## Navigable maps of structural brain networks across species
[![DOI](https://zenodo.org/badge/230978597.svg)](https://zenodo.org/badge/latestdoi/230978597)

This repository contains the maps in hyperbolic space of the 26 structural connectomes used in the article

_Navigable maps of structural brain networks across species_<br>
Antoine Allard and M. Ángeles Serrano<br>
PLOS Computational Biology (2020)<br>
DOI: [10.1371/journal.pcbi.1007584](https://doi.org/10.1371/journal.pcbi.1007584)<br>
arXiv: [arXiv:1801.06079](https://arxiv.org/abs/1801.06079)

Most of the structural connectome datasets used are available publicly. See _S01 Appendix_ for a description of the datasets, references to the original publications and download information (when applicable).

Except for the Mouse1, Human3, Human4, Human5 and ZebraFinch1 datasets, which have been shared with us privately, the corresponding edgelists is also provided (i.e., the structural connectome).


#### Hyperbolic maps

Maps are provided via text files containing the coordinates of each node in the hyperbolic disk. Each line corresponds to a single node and has the following format:
```
[name of the node] [radial position] [angular position]
```


#### Edgelists

The edgelists are provided as text files in which each line corresponds to a link and follows the format:
```
[name of the node 1] [name of the node 2]
```
Note that some links may appear more than once in the edgelist.
