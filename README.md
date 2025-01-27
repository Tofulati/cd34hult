# HULTCD34 starCAT analysis

We are using exist references and the hultCD34 dataset to produce a usage GEPxgene matrix. Using the resulting matricies, we can compare the two to see whether starCAT is correctly producing results.

File details:
- starCAT dataset analysis and creation of result usage matrix
- correlation plots and umapping comparing starCAT and cNMF usage matricies (_viz.ipynb)
- reference datasets for starcat
- usage csvs for output of starcat and existing cnmf 

Current known issues:
- data may have issued with correlation values
- data may be orocessed incorrectly, paper shows backwards matrix factorization
- correlation umap with normalized data looks blurry

> Still working on, there will be bugs and issues