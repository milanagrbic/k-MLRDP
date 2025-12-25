# k-MLRDP

This repository contains datasets, executable versions, and experimental results associated with the paper:

**Multiplex Roman Domination: Efficient Algorithms for Complex Network Control**  
**Authors:** Milana Grbic, Nenad Vilendecic, Aleksandar Kartelj, Dragan Matic

## Overview

The repository provides all instances, executables, and detailed results used in the experimental evaluation of the *k-Multiplex Roman Domination* problem.  
It is intended to support reproducibility of the experiments and further research on Roman domination problem in multiplex networks.

## Repository Structure

The repository is organized into three main directories:

k-MLRDP/
│
├── Instances/
├── Exec/
└── Results/


### 1. Instances

This folder contains the multiplex network instances used in the paper.

- The instances are divided into **three classes**, each stored in a separate subfolder.
- Each **instance** is stored in its own directory.
- Inside each instance directory:
  - Each **layer** of the multiplex network is provided as a separate file.

#### Layer File Format

Each layer file is structured as follows:

- **First line:**  

<number_of_nodes> <number_of_edges>

- **Subsequent lines:**  
Each line represents one edge of the layer, given as a pair of nodes:
u v


Each edge is listed on a separate line.

### 2. Exec

The `Exec/` directory contains:

- Executable versions of  GA and VNS algorithms proposed and evaluated in the paper.
- Example commands illustrating how to run the algorithms on the provided instances.

These executables were used to generate the experimental results reported in the study.

### 3. Results

The `Results/` directory contains **detailed experimental results**.

- Results are organized into subfolders **by algorithm**.
- Each subfolder includes the corresponding output data produced during the experiments.


## Notes

- All instances and results correspond exactly to those used in the paper.
- The repository is intended for research and academic use.
- If you use this repository in your work, please cite the corresponding paper.

## Contact

For questions or additional information, please contact the corresponding author:
milana.grbic@pmf.unibl.org
