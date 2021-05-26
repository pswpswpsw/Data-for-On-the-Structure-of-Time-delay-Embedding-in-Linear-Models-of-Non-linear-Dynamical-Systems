# Description

Here is the POD coefficient data for the paper [On the Structure of Time-delay Embedding in Linear Models of Non-linear Dynamical Systems](https://aip.scitation.org/doi/10.1063/5.0010886)

The data is collected by direct numerical simulation of a 3D incompressible N-S equation in [OpenFOAM](https://www.openfoam.com/). Details can be found in the [paper](https://aip.scitation.org/doi/10.1063/5.0010886). Then, large-scale memory-distributed SVD is performed by [Nicholas Arnold-Medabalimi](https://scholar.google.com/citations?user=u9S9yVUAAAAJ&hl=en). 

## Parameters:
- Ra = 10^7
- Pr = 1.0

## How it is used in the paper?
Here are the POD coefficients in the Matlab **mat** file format with different SVD truncations to illustrate the trend of "optimal" delay in the paper.

## Citation


    @article{pan2020structure,
    title={On the structure of time-delay embedding in linear models of non-linear dynamical systems},
    author={Pan, Shaowu and Duraisamy, Karthik},
    journal={Chaos: An Interdisciplinary Journal of Nonlinear Science},
    volume={30},
    number={7},
    pages={073135},
    year={2020},
    publisher={AIP Publishing LLC}
    }
