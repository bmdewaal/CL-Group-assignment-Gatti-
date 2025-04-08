# Gatti study replication

## Overview

This repository contains code for training and applying uni-gram and bi-gram models for predicting word valence based on linguistic data. The project uses datasets from two key sources:

Gatti et al. (2024): Pseudoword data.
Speed & Brysbaert (2024): Word valence estimates and associated linguistic data.
Data Requirements

Important: Due to licensing restrictions and file sizes, the data is not included in this repository. You must download the datasets separately and place them inside a folder named data at the root of this repository.

## Data Sources

### Gatti Pseudowords Data:
Download the pseudoword dataset from Gatti and colleagues from Springer – Data Availability.
[Gatti Pseudowords Data:](https://link-springer-com.tilburguniversity.idm.oclc.org/article/10.3758/s13423-024-02487-3#data-availability)


### Speed & Brysbaert Data:
Download the dataset, including the prevalence Netherlands file, from OSF – Prevalence Netherlands File.
[Speed & Brysbaert Data](https://osf.io/jex9n)


## Setup Instructions

Create the Data Folder:
Ensure you have a folder named data in the root directory of the repository (e.g., /Users/bramdewaal/Desktop/Uni/VSC/CL/Group Assignment/data).
Download and Place Data Files:
After downloading, add the following files to the data folder:
BrysbaertValence.xlsx
data_pseudovalence.RData
prevalence_netherlands.csv

Run the Code:
With the data in place, you can run the provided scripts to preprocess the data, train the models, and predict valence values.

## FastText (text) model for Dutch
[Download the model here](https://fasttext.cc/docs/en/crawl-vectors.html). Make sure to download the bin model, not the text version, as text model can only be used for static embeddings, and we need the model's subword capabilities for pseudoword encoding.

## Usage
Before running the scripts, ensure your working directory is set to the repository's root. Detailed instructions on how to execute the scripts and analyze the results are provided within the code comments.
