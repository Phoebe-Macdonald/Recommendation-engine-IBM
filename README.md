# Recommendation-engine-IBM

## Motivation:
The following project builds a recommendation engines with recommends articles for users on the IBM Watson Studio platform.
It builds two forms of collaborative filtering recommendation engines:
- neighbour based
- model based using matrix factorization
Effective recommendations enable users to more easily find content of interest 

## Getting Started:
In order to run the following code you will need to:
- Install all prerequisites below
- Run 'jupyter notebook' in the terminal and run the code in 'Recommendations_with_IBM.ipnb'

### Prerequisites:

#### Data preparation
import pandas as pd
import numpy as mp

#### Data visualisation
import matplotlib as plt

### Files:
This repo contains the following folders and files
- Data - this folder contains data to build and test the recommendation engines
    - user-item-interactions.csv - a record for every interaction between a user and an article
    - articles_community.csv - information on the content in articles

- Recommenations_with_IBM.ipynb - a Jupyter notebook which holds the code to build and test recommendation engines

Tests and files to ensure the development of the recommendation engines is correct and bug free
- project_tests.py - 
- top_5.p
- top_10.p
- top_20.p
- user_item_matrix.p