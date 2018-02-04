# Evaluating GDP Forecasts
_André Binette_ <abinette@bankofcanada.ca>

_Dmitri Tchebotarev_ <dtchebotarev@bankofcanada.ca>

This repository contains the code required to reproduce the results published in the Bank of Canada Staff Analytics Note No. 21 titled "Evaluating real GDP growth forecasts in the Bank of Canada Monetary Policy Report", available [here](http://www.bankofcanada.ca/2017/11/staff-analytical-note-2017-21/).

The analytical code is contained in two notebooks:
* `forecast_errors_results` contains main results from the paper
* `forecast_errors_cpi_results` contains results calculated from CPI forecasts and presented in Appendix B

In order to run the code, you need a working [Jupyter](https://jupyter.org/) server.
It is recommended that you create an [Anaconda](https://www.anaconda.com/) environment with the supplied `environment.yml` file to avoid any issues with python package versioning.

## Interactive version
For those wishing to experiment, we invite you to clone the workbook for yourself using Microsoft Azure Notebooks.
Follow the link below and clone the library to run the notebook interactively.
The azure notebook library is generated directly from this repository and contains identical information.

[![Azure Notebooks](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/dmitri/libraries/evaluating-gdp-forecasts)
