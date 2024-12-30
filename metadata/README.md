# Precursor hazard screening

This repository contains the data and example code for chapter 5 of my thesis.

## Developers
Vincent Chung

## Dependencies
- Python3
- Numpy
- Pandas
- Sympy

## Installation
```
git clone https://github.com/vchung1263/precursor_hazard_screening.git
```
Note that the code have only been tested on running in Windows.

## Description

- The candidate_score.ipynb (editing) contains an example code of generating possible precursor recommandation for solid-state synthesis given a target oxide. The criteria used are based on the HHI (Herfindahl-Hirschman Index) of the element, the Abundance of elements in Earth's crust, and the hazard statements of the precursors.
- The ./data folder contains the curated data used to asign the HHI, scarcity, and hazard scores for 230 precursors used in solid-state synthesis (more info in ./data)


