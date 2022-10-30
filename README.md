# single_cell_analysis

Single cell RNA-seq data used here is generated using the 10X genomics platform.
FILE LINK  : https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM4476089
scRNA-seq measures the RNA molecules within each cell of a given sample.

Here the parameters used are:

counts: Un normalized data such as raw counts or TPMs

min.cells: Include features detected in at least this many cells. Will subset the counts matrix as well. 
To reintroduce excluded features, create a new object with a lower cutoff.

min.features: Include cells where at least this many features are detected.

Cell type identification using scRNA-seq traditionally involves two steps. First, the cells are clustered using an unsupervised method, and then the clusters are 
annotated to different cell types based on canonical markers found in the differentially expressed genes of the cluster .
