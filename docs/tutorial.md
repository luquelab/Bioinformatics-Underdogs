# Tutorial to implement Bioinformatic pipeline

## Step 1.
### Find 6 or more unknown proteins in DNA sequence form. Save your unknown sequences as a FASTA file called "sequences.fna". Format should be 
>Sequence_1
AAAATTTTCCCCGGG

## Step 2.
### Upload "sequences.fna" into the contents folder of the jupyter notebook "underdogs_pipeline. It is important to upload into contents folder or it won't work.

## Step 3. 
### Install prerequisite programs (Bypython and Clustal Omega).

## Step 4.
### Sequence Preprocessing
Run the initial code cells to:
Load and parse sequences.
Compute sequence lengths and GC content.
Generate basic visualizations (e.g., histograms, boxplots).
Translate DNA sequences into proteins.

## Step 5
### Perform Multiple Sequence Alignment (MSA)
Use Clustal Omega to align protein sequences. Run the alignment cell and save the aligned output in both FASTA and Clustal formats.

## Step 6
### Conservation & Distance Analysis
After alignment:

Compute conservation scores to identify conserved regions.
Generate a distance matrix based on sequence similarity.

## Step 7
### Phylogenetic Tree Construction
Build a phylogenetic tree using the UPGMA method. Save the tree in Newick, PhyloXML, and SVG formats.

## Step 8
### BLAST Search (NCBI nr Database)
Run the BLAST search to compare translated protein sequences against the NCBI nr database. Save the results in CSV format for further interpretation.
