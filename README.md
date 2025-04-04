# MAP565 - French Energy Consumption Analysis

Authors: Adrien Bindel, Nathan Boughalem-Salier, Victor Deshors, Félix Rosseeuw

## Getting started

### Retrieve the data

In the terminal, run `unzip consommation-quotidienne-brute-regionale.zip` 

### Python libraries

To execute the notebooks, you will need the following library installed:
- numpy
- pandas
- matplotlib
- seaborn ?
- [statsmodels](https://www.statsmodels.org/) ?

You will find the LaTeX report at:  
https://www.overleaf.com/6354411123cxcmzdyjkyjz#1185f0 (link for editing)  
https://www.overleaf.com/read/htmkyhhhvpgd#516bf0 (view only)

In file `documents_pour_memoire`, you will find all the resources to illustrate the report with plots (and the comments associated to them).

## Structure of the code

`statistical_analysis.ipynb` notebook de base de ce que eux avait fait avec tous les processus dans le même notebook
`arima.ipynb` for the auto-regressive models
`copules.ipynb` for the copules
`garch.ipynb` for the garch model

## Name
French Energy Consumption Analysis with Stochastic Models

## Description
We have chosen to delve into the French energy consumption public data bank.

We will try to apply tools studied in Stochastic Modelisation class to give some insight on the data provided. This will include some notions like:
- copula
- Gaussian processes
- Hawkes processes

Links to data:  
https://www.data.gouv.fr/fr/datasets/consommation-quotidienne-brute/  
https://www.data.gouv.fr/fr/datasets/consommation-quotidienne-brute-regionale/

## Contributing
This project is open for any improvement you may come up with.

## License
Don't know. It is a mandatory school projet.

## Project status
This project is still in development...