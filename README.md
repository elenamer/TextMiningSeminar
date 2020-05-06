# TextMiningSeminar

## Prerequisites

Python version 3.8 or higher

## Create the Conda environment

```python
# create the environment with the required packages
conda env create -f environment.yml
# to activate the conda environment run
conda activate tm-seminar-elena-env
```

## Extract the data 

Download the corpus.sqlite3 file into the project root from [here](https://github.com/tblock/10kGNAD/releases/download/v1.0/corpus.sqlite3)

Run ```bash python code/extract_dataset_from_sqlite.py corpus.sqlite3 articles.csv``` to extract the articles.

## Folder structure

| Folder   |      Description      | 
|----------|-------------|
|Notebooks |  the folder with the notebooks, which calculate the embeddings and run classifiers |
| code     |    script to extract the data    |
| visualizations | images and tables to evaluate results | 