# BiopythonSearchEngine

This code takes an input FASTA file(.fa) and receives data from BLAST search results from the nucleotide database using Biopython. In order to run this code, one will need to have Biopython installed using the Terminal Line commands shown below on Mac or Command Prompt for Windows. One can also use the fasta_string variable in different functions or loops to scan for certain codons and proteins as well. This code can take a few minutes to run due to the sheer size of the nucleotide database. The code is designed to work in a Jupyter Notebook.

Terminal Line(Mac) or Command Prompt(Windows):
pip install biopython

What it does:
Imports the NCBIWWW and NCBIXML modules from Biopython
Asks for the path of the input FASTA file(.fa)
Converts all the text in the file into a string(fasta_string)
Uses the qblast function from NCBIWWW to get the results of the BLAST search against the nucleotide("nt") database
Reads these results into the variable blast_record
Prints the alignments
