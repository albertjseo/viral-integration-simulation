# Viral Integration Simulation

### Introduction
A personal project that explores a bioinformatics analysis pipeline that simulates viral integration events 
in host genomes. This personal project is inspired by [A bioinformatic pipeline for simulating viral integration data.](/https://pmc.ncbi.nlm.nih.gov/articles/PMC9046613/#bib0002)
### Aim
IN CONSTRUCTION


<img src="https://img.shields.io/badge/language-Python-blue.svg" style="zoom:100%;" />

### Workflow
This project uses [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) to run the 
bioinformatics pipeline using <mark style="background-color:grey">snakemake</mark>.

Creating the git repo.
```
 1.) Create the git repo
 2.) Ensure you are in the correct folder
        cd ~/foldername
 3.) clone git repo
        git clone HTTPS link
```
Creating Conda environment
```
conda create -n snakemake -c conda-forge -c bioconda snakemake -y
conda activate snakemake
```
