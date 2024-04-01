# Learning Descriptors for Novelty-Search Based Instance Generation via Meta-evolution

## Authors

* Alejandro Marrero: amarrerd@ull.edu.es
* Eduardo Segredo: esegredo@ull.edu.es
* Emma Hart: e.hart@napier.ac.uk

## Abstract
The ability to generate example instances from a domain is important in order to benchmark algorithms and to generate data that covers an instance-space in order to train machine-learning models for algorithm selection. Quality-Diversity (QD) algorithms have recently been shown to be effective in generating diverse and discriminatory instances with respect to a portfolio of solvers in various combinatorial optimisation domains. However these methods all rely on defining a \textit{descriptor} which defines the space in which the algorithm searches for diversity: this is usually done manually defining a vector of features relevant to the domain. As this is a limiting factor in the use of QD methods, we propose a \textit{meta-QD} algorithm which uses an evolutionary algorithm to search for a non-linear 2D projection of an original feature-space such that applying novelty-search method in this space to generate instances improves the coverage of the instance-space. We demonstrate the effectiveness of the approach by generating instances from the Knapsack domain, showing the meta-QD approach both generates instances in regions of an instance-space not covered by other methods, and also produces significantly more instances.

# Relevant information

- Source code: DIGNEA, available [here](https://github.com/DIGNEA/DIGNEApy)
- $NS_f$ 8D results from PPSN are available [here](https://github.com/PAL-ULL/ns_kp_generation)
- $NS_{pca}$ results from GECCO 23 are available [here](https://github.com/PAL-ULL/ns_pca_gecco23)
