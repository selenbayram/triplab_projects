# Repository: triplab_projects 
(Summer 2023, TripLab)

This repository consists of the code written during June-August 2023 summer research training.

### Project: Cross-Modal Data Integration Using Seurat

#### Description
Cross-modal data integration using smart-seq and patch-seq datasets with Seurat's Bridge Integration method to infer electrophysiology properties of neuronal cells based on gene expression and vice versa.

#### Datasets
Allen Institute smart-seq dataset with gene expression <br />
Allen Institute older datasets with electrophsiology data <br />
Gouwens et al. 2020 patch-seq dataset with both electrophysiology and gene expression

#### Research Questions
1- Can we infer cell type identity (t-type) for cells for which only the electrophysiology data is available? <br />
2- Can we infer electrophysiological properties for cells using the associated gene expression data? <br />
3- Can we infer gene expression based on electrophysiology data on cells? <br />

#### Initial Steps
0- Set up VSCode and remote access to SCC; get correct versions of R and Seurat; learn R <br />
1- Perform clustering and UMAP analysis on mouse smart-seq dataset used for 2022 KCNI Summer School <br />
2- Perform clustering and UMAP analysis on Gouwens patch-seq dataset <br />

#### Useful Papers and Links
Seurat scRNA-seq integration : https://satijalab.org/seurat/articles/integration_introduction.html#performing-integration-on-datasets-normalized-with-sctransform <br />
Seurat Bridge Integration: https://satijalab.org/seurat/articles/seurat5_integration_bridge.html <br />
Gala et al. 2021 : https://www.nature.com/articles/s43588-021-00030-1 <br />
Gouwens et al. 2020 : https://www.cell.com/cell/pdf/S0092-8674(20)31254-X.pdf <br />
Hao et al. 2023 : https://www.nature.com/articles/s41587-023-01767-y <br />
Kalafut et al. 2023 : https://www.nature.com/articles/s42256-023-00663-z <br />
Li et al. 2023 : https://doi.org/10.1016/j.cell.2023.03.023 <br />
