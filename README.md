# NRCS-CN_Ia_analysis: NRCS-CN analyses from large samples (CARAVAN)

The code within this repository is founded on the analysis of the Natural Resources Conservation Service Curve Number (NRCS-CN) method and its parameters. The analyses make use of the [CARAVAN dataset and your extensios] (https://zenodo.org/records/6578598). The separation of streamflow into baseflow and runoff is based on the methodology established by Xie et al. (2020) (https://doi.org/10.1016/j.jhydrol.2020.124628).

Contained within this repository are 5 Jupyter Notebooks, each focused on the application of the NRCS-CN method using distinct data analysis approaches:
- Principal Components Analysis
- Random Forest
- NRCS-NEH
- NRCS-ASYMPTOTIC
- NRCS-LEAST-SQUARES

Additionally, the results of the metrics from applying these methods can be found in the files Metrics_runoff_G1 and Metrics_runoff_G2. The folder Times_series contains the time series of simulated runoff using the NRCS methods.

The results are available: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10962037.svg)](https://doi.org/10.5281/zenodo.10962037)
