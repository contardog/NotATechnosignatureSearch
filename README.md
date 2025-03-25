# 

## Code and some data product for a data-driven search for excess in the Mid-Infrared in 4.9M FGK main-sequence stars 

Paper: https://iopscience.iop.org/article/10.3847/1538-3881/ad6b90 (it contains the ADQL query for Gaia DR3 data selection and cross-matching in the Appendix) 

Notebook contains code to reproduce figures and part of the pipeline for the identification of our candidates.

CSV files contains either Gaia DR3 source id, 2MASS ID, ra and dec for the 53 objects (53candidates_small.csv), or all the columns obtained when cross-matching Gaia DR3, 2MASS, AllWISE, UnWISE + the outputs of the 8-folds models and other masks processed (53candidates_allcol.csv). 



TO DO: 
* Upload intermediate data-products (? if doable.. the full unwise_merge file is 23Gb...)
* Upload scripts for cross-matching and data grabbing to reproduce
* Upload scripts / code for the training of the 8-folds.
* Make a better README
* Columns names in the table...

  
