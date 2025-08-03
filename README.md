# Projeto Final QuantumFinance Credit Scoring - MLOps - 9dtsr 2025

Este é uma projeto realizado como parte final da entrega da disciplica de Machine Learning Engineering - MLOps, 
onde tem como objetivo criar um fuxo end-to-end da analise para um sore de credito do cliente da QuantumFinance.

Nele contempla desde a analise do <a target="_blank" href="https://www.kaggle.com/datasets/parisrohan/credit-score-classification">dataset<a/> 
para pré-processamento e criação do modelo preditivo até a disponibilização de um frontend para consumo deste modelo.

Neste repositorio (fiap-ds-mlops-9dtsr-credit-scoring) temos toda a estrutura de modelagem, construção e versionamento dos
dados e o seu notebook.

Projeto Final QuantumFinance

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         fiap_ds_mlops_9dtsr_credit_scoring and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── fiap_ds_mlops_9dtsr_credit_scoring   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes fiap_ds_mlops_9dtsr_credit_scoring a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

## Config Template Cookiecutter

python -m pip install --user pipx

python -m pipx ensurepath

pipx install cookiecutter-data-science

ccds (Na pasta onde quer criar o projeto)

--------

