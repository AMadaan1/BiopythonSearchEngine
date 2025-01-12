# BiopythonSearchEngine
This code takes an input FASTA file(.fa) and receives data from BLAST search results from the nucleotide database using Biopython. In order to run this code, one will need to have Biopython installed using the Terminal Line commands shown below on Mac or Command Prompt for Windows. One can also use the fasta_string variable in different functions or loops to scan for certain codons and proteins as well. This code can take a few minutes to run due to the sheer size of the nucleotide database. The code has been designed and tested in Jupyter Notebook.

Terminal or Command Prompt commands ARE nessecary in order to run this code.

pip install biopython

What it does:
  
  1. Imports the NCBIWWW and NCBIXML modules from Biopython
  
  2. Asks for the path of the input FASTA file(.fa)
  
  3. Converts all the text in the file into a string(fasta_string)

  4. Asks which records to search(1 would be the first record)
  
  5. Uses the qblast function from NCBIWWW to get the results of the BLAST search against the nucleotide("nt") database
  
  6. Reads these results into the variable blast_record
  
  7. Prints the alignments
