# Analyzing COVID RNA Sequences
This project involves downloading and analyzing RNA sequences of COVID-19, focusing on two of its major variants: Delta and Omicron. RNA is a nucleic acid present in any living cell that has one strand consisting of various combinations of four nucleotides: uracil, cytosine, adenine, and guanine. RNA is the "source code" for COVID-19 that enables the virus to enter the cell and replicate itself.

## Project Overview

In this project, we will:
1. Load and explore metadata containing unique identifiers and other information about existing COVID-19 RNA sequences.
2. Identify specific RNA sequences to analyze.
3. Download the actual nucleotide sequences for the selected COVID-19 RNA sequences.
4. Parse the RNA sequences and convert them into a readable format.
5. Align the RNA sequences to analyze mutations and differences between variants.

## Dataset

We will be using data from the NIH (National Institutes of Health). You can download the dataset containing the metadata for each COVID-19 RNA sequence from [this link](https://drive.google.com/file/d/1S2ZDjdRkY78kZxBtc9YNUh0mByTHXQ23/view) and look at its documentation [here](https://www.ncbi.nlm.nih.gov/datasets/docs/v1/data-packages/sars-cov-2-genome/).

## Project Structure

The project consists of the following files:
- `covid_genome.ipynb`: Jupyter notebook for the project.
- `ncbi_datasets.csv`: CSV file containing metadata for COVID-19 RNA sequences.

## Installation

To run this project, you need to have Python and Jupyter Notebook installed. You also need to install the required libraries:

```sh
pip install pandas biopython matplotlib
