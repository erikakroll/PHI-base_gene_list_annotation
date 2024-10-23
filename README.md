# PHI-base gene list annotation
A set of Jupyter lab notebooks that can be used for annotating sets of protein IDs with information from PHI-base

PHI_base_Uniprot_Search_cleaned.ipynb take in line seperated UniProt IDs and searches for them in PHI-base database, then prints a table with the following information: Uniprot ID, PHI-base ID, Gene_name, Organism, and Phenotype. 

PHI_base_NCBI_all_hits_cleaned.ipynb is meant to be paired with PHI-BLAST function provided by http://www.phi-base.org/downloadLink.htm. From PHI-BLAST the notebook makes a table of only the top BLAST hit including PHI-base ID, Gene Name (from PHI-base), Organism, and Phenotype. The notebook requires BLAST input data to be in NCBI format. To identify perfect matches only (i.e. searching for hits within the same species as input IDs) set E-value threshold of BLAST to 0. 

PHI-base database version used in this example is v4.16 downloaded from http://www.phi-base.org/downloadLink.htm. 
