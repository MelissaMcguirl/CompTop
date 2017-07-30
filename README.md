# CompTop

This repository contains scripts for using Ripser (https://github.com/Ripser/ripser) and 
Hera (https://bitbucket.org/grey_narn/hera) with a Python interface. 

1. To run Ripser on a collection of distance matrices use getBarCodes.py
2. To separate Ripser output by dimension to a input that is compatible with Hera, use separateRipser.py 
   IMPORTANT: Code assumes there are just dimension 0 and dimension 1 barcodes. Code can be adapted easily. 
3. To plot PDs, use plotPDs.py (Must use output of separateRipser, not output of getBarCodes.py)

Author: Melissa McGuirl
Contact: melissa_mcguirl@brown.edu
