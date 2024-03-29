# genomics-study-group


This is a self-study guide for learning [genomics](https://www.genome.gov/about-genomics/fact-sheets/A-Brief-Guide-to-Genomics), a sub-discipline of [biotechnology](../README.md).

Current focus is on [Genomic Signal Processing](https://nodeholder.notion.site/Genomic-Signal-Processing-eb48c90f0f6d49a481bc498421879d64)

## Background

The fundamentals of bioinformatic data science are based on [information theory](https://bioinformaticshome.com/bioinformatics_tutorials/sequence_alignment/introduction_to_information_theory.html)  and [sequential sequence processing](./papers/2007-BootstrapParticleFilteringSPMagCandy.pdf).

The StatQuest video [A gentle introduction to RNA-seq](https://www.youtube.com/watch?v=tlf6wYJrwKY) by Josh Starmer is a good introduction to the field of applied bioinformatics, specifically indentifying and relating sequences of base pairs from [PCR](https://www.youtube.com/watch?v=7beN35g5xuM).

Gene folding is more complex, [Demis Hassabis of Deep Mind](https://lexfridman.com/demis-hassabis/) frames the next 50 years of work. For technical background, [Principles of protein folding--a perspective from simple exact models](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2143098) is a decent 
technincal starting place.

## In Practice
A practical nexus of gene sequencing and protien folding is the the [Blast site at Ncbi](https://blast.ncbi.nlm.nih.gov/Blast.cgi). This is a [good video](https://youtu.be/WRKQGwh_Mw0) that explains the Blast site.

The [Rosalind](http://rosalind.info/problems/tree-view/) project provides challenge problems as described by [Bioinformatics Algorithms](https://www.bioinformaticsalgorithms.org/) by Phillip Compeau and Pavel Pevzner.

Transformers are at the heart of everything. Here is DeepMind's [AlphaFold 2 Explained](https://www.youtube.com/watch?v=B9PL__gVxLI) by Y. Kikcher.

## Reivewed in 2023

- [Node embedding for Predictin Disease Genes](https://github.com/lucacareddu/Comparing-node-embedding-methods-and-classifiers-for-predicting-disease-genes):  Python code of the work done for the masters project "Learning from Networks". Uses Karate Klub for graph embeddings.

- [Brown, CS 181: Computational Molecular Biology](http://cs.brown.edu/courses/cs181/lectures.html): decent college level course on DNA sequencing.


## Resources
- [Glossary of Next Gen Sequencing](https://www.illumina.com/science/technology/next-generation-sequencing/beginners/glossary.html): terms used in in NGS defined by Illumina. Video overview: [NGS for beginners](https://www.illumina.com/science/technology/next-generation-sequencing/beginners.html).

- [Bioinformatics Algorithms](https://www.bioinformaticsalgorithms.org/): Book and methodology by Phillip Compeau and Pavel Pevzner. Great.

 - [DNA Analysis on Coursera by Pavel Pevzner and Phillip Compeau](https://www.coursera.org/learn/dna-analysis): 8 part course on DNA statistics.
  
- [Rosalind](http://rosalind.info/problems/locations): Rosalind is a platform for learning bioinformatics and programming through problem solving.

## Data Sets
- [Google genomics data sets](https://cloud.google.com/genomics/docs/public-datasets/) Cloud Genomics provides a variety of public datasets that you can access for free and integrate into your applications. Google hosts these datasets, providing public access to the data.

## Software
- [HCA](https://mloss.org/software/title/?page=11) Multi-core non-parametric and bursty topic models (HDP-LDA, DCMLDA, and other variants of LDA) implemented in C using efficient Gibbs sampling, with hyperparameter sampling and other flexible controls.
