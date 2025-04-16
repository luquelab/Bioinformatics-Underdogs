## Function of Pipeline
### This pipeline functions to identify a set of unknown nucleotide sequences by using bioinformatic tools and accessing databases. Additionally, this pipeline serves to compare the sequences to one another and produce figures with identifying information and comparison. 

## Steps involved:
### First the sequences are translated from nucleotide form to amino acids. Also basic information like sequences length and GC content are plotted this is done using Biopython.

## Second the sequences are compared in a multiple sequence alignment using Clustal Omega. This will create a consesus plot of conserved regions and a pairwise distance heatmap. 

### Third we can identify the taxa of our sequences by accessing NCBI BLASTp (non-redundant sequences). This will run a BLASTp on each sequence. Be patient as this can take a long time. Outputs will include the top organisms identified as well as a more sequence-specific identity. This code will also display the function and organism per sequence.
