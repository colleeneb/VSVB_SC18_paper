# VSVB_SC18_paper
This is a public repository for structures in the SC18 submission "Quantum Chemistry on a Million Processes"

It contains VSVB inputs for:
1. 64-atom LiF crystal structure 
2. 128-atom LiF crystal structure

The input files contain structures, basis functions, and thresholds.

Input files can be run after the VSVB executable is compiled by:

$ ./vsvb-executable < vsvb_input_file

Note about thresholds:

In the second line of the input files, the numbers "9 9 8" denote that the charge-cloud screening tolerance is 10^-9, the density screening tolerance is 10^-9, and the Schwarz inequality screening tolerance is 10^-8. 
