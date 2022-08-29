# 🪙 `Check Out Our GitCoin Grant!` 🪙
> [![Gitcoin](https://img.shields.io/badge/GitCoin-New%20Atlantis-F3587D)](https://gitcoin.co/grants/7126/new-atlantis-ocean-biodiversity-restoration-resci)

# 🧬 `Metagenomics`

> The metagenomic pipeline section of the new atlantis github. An easy-to-use pipeline for generating metagenomic data on different ocean samples.
Currently known as the `Large Plankton Processor` or `LPP` for short.

> [![Discord](https://img.shields.io/badge/Discord-New%20Atlantis-7289da)](https://discord.gg/newatlantis)
[![Twitter](https://img.shields.io/badge/Twitter-%40NewAtlantisDAO-00acee)](https://twitter.com/NewAtlantisDAO)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/new-atlantis-dao/Metagenomics/blob/8503d74f9769b7201a174f203781e5d6b9f72cb9/notebooks/Custom_DB_MTG/CustomDB_MTG_Taxa_Profiling_v1.0.ipynb)

![Main Image](https://github.com/new-atlantis-dao/presentations/blob/main/OrcaEye%20PN%20Watermarked.png)




## 🪄 Try it Now!
You can set up and use the `LPP` on the cloud by following along the google colab notebook

> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/new-atlantis-dao/Metagenomics/blob/8503d74f9769b7201a174f203781e5d6b9f72cb9/notebooks/Custom_DB_MTG/CustomDB_MTG_Taxa_Profiling_v1.0.ipynb)

Please note that google colab does not provide the computational resources necessary to fully run `LPP` on a real dataset. This notebook demonstrates how to setup and use `LPP` by performing the first steps in the workflow on a toy dataset.


## ⚙️ Installation
You can set up `LPP` on your computer at home in one line!
```
git clone https://github.com/new-atlantis-dao/Oceanomics/tree/main/Metagenomics && cd Metagenomics && rm -r .git
```
Congratulations, you can now start using `LPP`.

## 📯 Tutorial
`LPP` can be used to explore  a local section of ocean's planktonic network. A written tutorial on how to use the `LPP` pipeline will be released at a later date.

> ![Tutorial](https://img.shields.io/badge/LPP-Tutorial-%23d8b365)

## 🗺 Data Structure
![DAG image](https://github.com/new-atlantis-dao/presentations/blob/main/Github%20MTG%20Pipeline%20background.png)


## 🗂 Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

## 📜 Publications
### Software and marker gene sequences used to build a plankton specific database for taxonomic profiling derive from the following publications:

#### [Microbial abundance, activity and population genomic profiling with mOTUs2 (2019)](https://www.nature.com/articles/s41467-019-08844-4)    
> [![Nature](https://img.shields.io/badge/Nature-s41467--019--08844--4-F39B7F)](https://www.nature.com/articles/s41467-019-08844-4)


#### [read_counter](https://github.com/AlessioMilanese/read_counter)      
A tool to count the number of reads (from a fastq file) that map to a set of nucleotide sequences (in a fasta format).      
> [![Github](https://img.shields.io/badge/GitHub-read_counter-6e5494)](https://github.com/AlessioMilanese/read_counter)


#### [A robust approach to estimate relative phytoplankton cell abundances from metagenomes (2022)](https://onlinelibrary.wiley.com/doi/full/10.1111/1755-0998.13592)      
> [![DOI](https://img.shields.io/badge/DOI-10.1111%2F1755--0998.13592-B31B1B)](https://onlinelibrary.wiley.com/doi/full/10.1111/1755-0998.13592)

#### [Toward a global reference database of COI barcodes for marine zooplankton (2021)](https://link.springer.com/article/10.1007/s00227-021-03887-y)    
> [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs00227--021--03887--y-B31B1B)](https://link.springer.com/article/10.1007/s00227-021-03887-y)

## 📝 Please Cite
```
A simple Taxonomic Plankton Profiler Tool (unpublished work).
```

## 📲 Contact
Please reach out with any comments, concerns, or discussion regarding `LPP`

> [![Discord](https://img.shields.io/badge/Discord-New%20Atlantis-7289da)](https://discord.gg/newatlantis)
[![Twitter](https://img.shields.io/badge/Twitter-%40NewAtlantisDAO-00acee)](https://twitter.com/NewAtlantisDAO)
[![Email](https://img.shields.io/badge/Email-tom%40newatlantis.io-%23ffce00)](tom@newatlantis.io)
