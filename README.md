## Sequence Alignment and Analysis with Python

### Sequence Retrieval and Pre-processing

In the study, a Python code snippet was first written to retrieve the amino acid sequences of three proteins belonging to the cytochrome P450 family with UniProt IDs: **P08684**, **P10635**, and **P11712** using Biopython's Entrez module.
The sequences were saved in FASTA format using an automated process. Use Biopython to parse the FASTA files and prepare the sequences for alignment.
A section was added to check for common problems in sequence data that could affect the alignment.


### Pairwise Sequence Alignment

Biopython's **pairwise2** module was used to perform alignments with various scoring matrices and gap penalty schemes.
The script allowed easy tuning of parameters to test different alignment strategies.
Detailed information about the alignment was provided, including score, matches, mismatches, gaps, and sequence identity/similarity percentages.
