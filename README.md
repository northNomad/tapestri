# Overview
`tapestriR` is an R package for DNA and DNA + Protein analysis of data generated by the Tapestri platform.
For additional documentation and tutorials visit: https://missionbio.github.io/tapestri_multiomics/

# Installation

**Not compatible with R >= 4.0.0.** Please use R 3.6.x. 

1) Install `devtools` and `BiocManager`.
2) Install `TaprestriR`. 
3) Start with loading_data.Rmd in the vignettes directory. 


Packages to help dependencies
```r
install.packages(c("devtools","BiocManager"))
```

Some users have reported defficultly in installing `rhdf5`. Users reported better luck using anaconda. Additional documentation for `rhdf5`: https://www.bioconductor.org/packages/release/bioc/html/rhdf5.html
```r
BiocManager::install("rhdf5")
```
Install the Tapestri R package
```r
devtools::install_github("MissionBio/tapestri_multiomics")
```
Start using it. 
```r
require(TapestriR)
```
For tutorials visit: https://missionbio.github.io/tapestri_multiomics/

# Usage
The purpose of this package is to enable easy loading of Tapestri data from various sources. The vignettes offer multiple examples of how to analyze these data, but it’s left to the user to explore the wide range of our packages to gain insights. For an easy-to-use solution, check out Tapestri Insights at https://portal.missionbio.com/. 

# Getting help
If you have any questions or need more information about this R package or the methods it implements, please contact Anup at parikh@missionbio.com. You can also post questions to the github repository. 

# License
AGPL-3
