# codon-optimization
Read in a protein sequence and generate a nucleotide sequence optimized for *E. coli* or *M. smegmatis*.

## Summary

This notebook uses hard-coded optimized codon tables to generate codon-optimized sequences.

Codon tables were derived from the [Codon Table Database](https://www.kazusa.or.jp/codon/). Rarely used codons (with occurence of below ~0.05) were set to a frequency of 0, and frequency of synonymous codons were adjusted to compensate.

Codons are randomly selected based on their tabulated frequency. Ten optimized sequences are generated in FASTA format.

Use the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/krs-lab/codon-optimization/blob/main/KRS_codon_optimization.ipynb)

