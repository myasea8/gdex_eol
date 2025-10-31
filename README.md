# Observation and Model Comparison Cookbook
This project compares ERA5 reanalysis data to EOL's 449MHz Wind Profiler dataset for the M2HATS field campaign, using the GDEX and NSF NCAR's HPC resources. 

## Motivation
This repository features a collaboration between NSF NCAR's Earth Observing Laboratory (EOL) and Computational and Information Systems Laboratory (CISL), which intends to demonstrate the use of HPC resources and the GDEX to improve a current internal workflow. 

The workflow that was previously used to comapare model data and EOL's observations involved many cumbersome steps -- a 96-hour programmatic request process for two months of ERA5 data and a manual data request, download, and untar/unzip for a field campaign's 449MHz Profiler data -- and largely occurred on an internal server, inhibiting sharing opportunities with PIs and collaborators. This new workflow utilizes the ERA5 reanalyses data hosted on GDEX, and has reduced the data request time from 96 hours to 18 seconds. Additionally, the new workflow experiments with hosting the wind profiler dataset as a zarr store on the GDEX, eliminating the necessity to download the dataset and greatly reducing the number of steps it takes to align and read in the data. 

## Getting Started
TBD

## Help
TBD
