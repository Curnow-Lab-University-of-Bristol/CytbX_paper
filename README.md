# CytbX_paper
This repository contains data and code from Hardy et al, PNAS (2023) 120(16):e2300137120

File '4D2_transformed.pdb.txt' is the input PDB file. This is a water-soluble de novo protein that forms a 4-helix diheme bundle, PDB ID 7AH0. See Hutchins et al, PNAS (2023) 120: e2306046120. https://doi.org/10.1073/pnas.2306046120

Other files are for Rosetta input, run according to 'design_script.xml.txt' and with options specified in 'flags.txt'. The specific positions to be mutated and the allowed amino acid alphabet at each position is dictated by the resfile 'resfile.txt'.

The single design output taken for further study is termed CytbX and the corresponding PDB file is 'Output_CybtX.pdb.txt'. 
