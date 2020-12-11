# Introduction

The following repository provides a Juniper notebook for generation of
[graphviz](https://graphviz.org/) code for attack tree visualization
and an Org file with common trees examples as were designed in the
H2020 [project Defender](https://defender-project.eu/). The common
trees provide an itemized description of the tree, graphviz sources
and a table with common tree node per node analysis. the repository is
therefore both the code needed to generate the attack tree
visualizations as wel a collection of the attack trees.

# Content

The following content is provided:

* generate_attack_tree_graph.ipynb: Jupyter notebook used for generation of the graphviz attack trees
* attack-trees.org: Org file with common attack tree examples
* graphs: a directory containing the common attack tree graphs examples
* at: an input directory for Juputer notebook

# Usage

For using the Jupyter notebook a [Jupyter](https://jupyter.org/)
environment with [Python](https://www.python.org/) kernel version 3.4+
is needed. In the repository directory run the jupyter server with the
following command and open the Jupyter notebook in the browser:

* jupyter notebook

Adapt the notebook parameters to your own needs and run the cell. The
output is the graphviz code needed to visualize the attack tree
specified in the input parameter. An Org mode table skeleton for attack
tree analysis can be provided as well.

# License

The attack tree repository is copyright (c) 2020 Jozef Stefan
Institute under the MIT license. See LICENSE for details.

# Contact

For comments and suggestions please contact dusan@e5.ijs.si.