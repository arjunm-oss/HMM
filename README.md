# Hidden Markov Model for Splice Site Detection

This is a small Python implementation of a Hidden Markov Model (HMM) used to test possible splice site positions in a DNA sequence.

The program calculates log probabilities for different state paths and predicts the most probable exon-intron transition.

## About the Model

States used in the model:

E → Exon

5 → Donor splice site

I → Intron

The model uses:
- transition probabilities between states
- nucleotide emission probabilities
- log probabilities to avoid underflow issues

## Input Sequence

The DNA sequence used in this project:


CTTCATGTGAAAGCAGACGTAAGTCA


Different possible splice positions are tested manually and compared based on probability scores.

## Files

hmm.py → main Python implementation of the HMM

## Concepts Used

- Hidden Markov Models
- State transitions
- Emission probabilities
- Log likelihood calculation
- Sequence analysis


The script prints:
- probability score for each tested path
- most probable state sequence

## Why I Made This

I made this mainly to understand how HMMs are applied in bioinformatics, especially for gene prediction and splice site identification.
