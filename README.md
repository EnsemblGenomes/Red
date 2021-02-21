# Red
Red: an intelligent, rapid, accurate tool for detecting repeats de-novo on the genomic scale. 

Requirement: GNU gcc8.2 or higher. Please change the name (CXX) of the compiler in the Makefile. 
  
Compiling the source code

The following command makes the required directories: 
> make bin

The following command makes the binary that is located under the ``bin'' directory:
> make 

To find the binary:
> cd ../bin

Please cite the following paper:

Girgis, H.Z. (2015) Red: an intelligent, rapid, accurate tool for
detecting repeats de-novo on the genomic scale. BMC Bioinformatics,
16, 227.

## Ensembl fork 

This fork adds option -frm 3 to produce 1-based inclusive coordinates for Ensembl,
as needed in https://github.com/Ensembl/plant-scripts
