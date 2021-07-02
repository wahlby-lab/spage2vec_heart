<!--[![bioRxiv shield](https://img.shields.io/badge/bioRxiv-10.1101/765842-red.svg)](https://doi.org/10.1101/2020.02.12.945345)-->
<!--[![DOI](https://zenodo.org/badge/239975864.svg)](https://zenodo.org/badge/latestdoi/239975864)-->

# De novo spatiotemporal modelling of cell-type signatures in the developmental human heart 

This repository contains a collection of code scripts and python notebooks for reproducing analyses and results from the original publication [1].
Instruction and code for training the spage2vec on the in situ sequencing data can be found in (spage2vec-pytorch-geometric). Analysis notebooks to reproduce results and figures can be found in 

Dependency: SpaGE (https://github.com/tabdelaal/SpaGE).

### Data Download
Raw in situ sequencing [2] and scRNAseq [3] data from Asp et al. [4] have been uploaded at: https://doi.org/10.5281/zenodo.5060858 under CC BY 4.0 license. Download and extract the content of the zipped archive in this repository local folder.

## References
[1] Sergio Marco Salas, Xiao Yuan, Christer Sylven, Mats Nilsson, Carolina Wählby, Gabriele Partel. "De novo spatiotemporal modelling of cell-type signatures in the developmental human heart".

[2] Wu, Chenglin; Qian, Xiaoyan; Nilsson, Mats (2019): ISS data in "A spatiotemporal organ-wide gene expression and cell atlas of the developing human heart". figshare. Dataset. https://doi.org/10.6084/m9.figshare.10058048.v1 

[3] Asp, Michaela (2021), “Developmental heart - filtered and unfiltered count matrices and meta tables”, Mendeley Data, V2, doi: 10.17632/mbvhhf8m62.2

[4] Asp, M., Giacomello, S., Larsson, L., Wu, C., Fürth, D., Qian, X., ... & Lundeberg, J. (2019). A spatiotemporal organ-wide gene expression and cell atlas of the developing human heart. Cell, 179(7), 1647-1660.
