# HULTCD34 starCAT analysis

We are using exist references and the hultCD34 dataset to produce a usage GEPxgene matrix. Using the resulting matricies, we can compare the two to see whether starCAT is correctly producing results.

File details:
- starCAT dataset analysis and creation of result usage matrix
- correlation plots and umapping comparing starCAT and cNMF usage matricies (_viz.ipynb)

Current known issues:
- starCAT reference is 35x2000 size, starCAT dataset isn't fully incorporating gene data
- correlation plots are incorrect, not showing comparison between two datasets
- umap of cNMF data isn't scaled correctly (not normalized)
    * created normized dataset (scikit minmax normalization)
    * correlation umap with normalized data looks blurry

> Still working on, there will be bugs and issues