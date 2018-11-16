# Relative Rate Computation

## Introduction

This simple pipeline will take as input a reference genome and VCF to compute the relative rate of mutations seen at each motif of a given length.

## Instructions

We recommend that you modify our provided `Snakemake` file to run our pipeline. 


## Tutorial

In the following example, we wish to compute the relative mutation rates of all 7-mers, but only considering singletons in our sample. 
This is the analysis performed by default using our `Snakemake` file.
