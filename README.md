# COVID RNA Sequence Analysis

## Project Overview:
This project downloads and analyzes RNA sequences of SARS-CoV-2 (COVID-19) and its major variants (Delta and Omicron).

### Goals
- Download metadata for COVID RNA sequences from NIH databases
- Retrieve actual RNA sequences for analysis
- Compare sequences across original COVID-19 and its major variants (Delta and Omicron)
- Analyze differences in RNA sequences

### Needs:
- List of COVID RNA sequences
- Actual sequences in readable format

### About RNA Sequences
RNA is the genetic material of the SARS-CoV-2 virus:
- RNA serves as the "source code" for the virus
- Enables the virus to enter cells and replicate
- Single-stranded (unlike DNA which is double-stranded)
- Consists of nucleotides: Adenine (A), Cytosine (C), Guanine (G), and Uracil (U)
  - Note: In sequence databases, Thymine (T) is often displayed instead of Uracil (U) by convention

### Data Sources
- National Institutes of Health (NIH) COVID-19 sequence databases
- Primary dataset: NCBI datasets.csv file containing sequence metadata
- Key metadata includes:
  - Sequence type (reference, variant)
  - Location of collection
  - Collection date
  - Sequence name
  - Sequence ID for retrieval

## Setup
This project uses Python with UV package manager and supports Jupyter notebooks via ipykernel.

## Getting Started
[Instructions to be added]