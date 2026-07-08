# Workflow 
## 1. Pepide scan: 
Upload your list of peptides and transcript fasta files to scan for the peptides in the +1, +2, and +3 translation frames.  
Check g:Profiler to check if the organism is listed under Ensembl genomes.  
If it is, then download the cdna file from Ensembl and upload that as transcript fasta.  
This is done so gene_ids are same in our analysis and g:Profiler.  
This generates the exact_hits_final_*.csv file.

## 2. Peptide hit count: 
Upload your exact hits final file and it your output will be a csv file with transcript/gene ids and number of peptides hitting in descending order.  

## 3. Orthology mapping to _Arabidopsis thaliana_:
In g:Profiler open the g:Orth tab.  
Choose your organism and set target to _Arabidopsis thaliana_.  
Paste your list of gene ids and run query.  
Download the csv file generated and you will also obtain a more detailed GO analysis.  

## 4. Mapping back to the peptides: 


