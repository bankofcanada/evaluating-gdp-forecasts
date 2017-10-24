# Evaluating GDP Forecasts
_André Binette_ <abinette@bankofcanada.ca>

_Dmitri Tchebotarev_ <dtchebotarev@bankofcanada.ca>

This repository contains the code required to reproduce the results published in the Bank of Canada Staff Analytics Note No. 21 titled "Evaluating real GDP growth forecasts in the Bank of Canada Monetary Policy Report", available [here](http://www.bankofcanada.ca/2017/11/staff-analytical-note-2017-21/).

The analytical code is contained in two notebooks:
* `forecast_errors_results` contains main results from the paper
* `forecast_errors_cpi_results` contains results calculated from CPI forecasts and presented in Appendix B

In order to run the code, you need a working [Jupyter](https://jupyter.org/) server.
It is recommended that you create an [Anaconda](https://www.anaconda.com/) environment with the supplied `environment.yml` file to avoid any issues with python package versioning.

## Interactive demo
For those wishing to simply experiment, we are presently providing an interactive version of the notebooks, available [here](http://ec2-35-182-249-174.ca-central-1.compute.amazonaws.com).
This allows you to run the code from our paper directly in your browser without needing to install any software.
Please note that the [tmpnb](https://github.com/jupyter/tmpnb) server providing the temporary notebooks only keeps notebooks alive for a maximum of 4 hours, or 1 hour of inactivity.
