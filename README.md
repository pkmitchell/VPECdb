# VPECdb
Veterinary Pathogenic E. coli database

## Installation and Usage
Stay tuned for a ready-to-use pipeline, but for now VPECdb is formatted for use with SRST2 for read-based virulence factor detection and ABRicate for assembly-based detetion using ABRicate.  

### Read-based using SRST2
Download the VPECdb_srst2.fasta file and enter it as the --gene_db for SRST2. Annotations should appear in the last column of the fullgenes__VPECdb__results.txt file.  
### Assembly-based using ABRicate
Create a VPECdb folder in your ABRicate db/ folder and copy the VPECdb_abricate.fasta file into that folder with the name "sequences". Then, run the ABRicate makedb routine and it VPECdb should appear as one of your available databases. 

## Current Targets
### Toxins
Shiga toxin 1  
Shiga toxin 2  
STa  
STb  
LT  
EAST1  
CNF1  
CNF2  
### Fimbriae/Adhesins
K88 (F4)  
K99 (F5)  
987P (F6)  
F17  
F18 (F107)  
F41  
F1845  
BFP  
CS31A  
Eae  

### Other
iutA  
iroN  
hlyF  
ompT  
iss/bor
