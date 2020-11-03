# Phylogeny_tutorial

The HTML version of this tutorial can be found [here](https://ndombrowski.github.io/Phylogeny_tutorial/)

Additionally, all input files (both needed but also the intermediate files) are provided in the Input_folder as well as the raw RMarkdown document that was used to document all code.

This tutorial is the written-up version by a lecture given by Dr. Anja Spang and Dr. Nina Dombrowski as part of a bioinformatics workshop in 2019 given for graduate students at the Royal Netherlands Institute for Sea Research (NIOZ) in the Netherlands.

The goal of this tutorial is to learn how to run a phylogeny using single as well as concatenated marker genes.

We have three proteins that are found in ~300 archaeal genomes and we want to create a phylogenetic tree for all three single proteins as well as generate a concatenated proteint tree.

This notebook will consist of two parts:

- A theoretical part going into the various aspects that are useful to know for phylogenetic analyses.
- A practical part. Here, we provide a set of protein sequences for which we want to generate trees.

The tutorial works on the NIOZ server named ada, where most tools are installed. The exception are custom scripts, which will be provided as part of this tutorial. If you work on a different system you need to set up programs, such as bmge, mafft, etc... yourself and change file paths if needed.

THe script catfasta2phyml.pl comes from: https://github.com/nylander/catfasta2phyml 
