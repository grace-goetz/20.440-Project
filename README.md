#README
This repo contains the data, variables, and code needed to organize the microbial phylum found in the tumor samples of Colorectal cancer, and compare the composition across stages. 

The Code folder holds the R script for the code to generate the Phylum Abundances plot across different stages in colorectal cancer. The code filters the metadata to include only Colorectal samples, and then separates into different stages. The metadata is then connected to the Kraken data for microbial changes, and filtered to include only phlyum. The abundances of each phylum for sample are summed and divided by the total number of samples in the stage, and plotted.

The data folder holds the Metadata and Microbial Abundances ("Kraken") for tumor samples derived from the cancer genome atlas. The microbial data was generated from the following citation https://github.com/biocore/tcga

The plots folder holds the finalized plot created by the above code. Mainly, plotting the Phylum abundances/total samples in stage of colorectal tumor samples across stages. 

You can run the code in R.
packages needed: dplyr, ggplot2