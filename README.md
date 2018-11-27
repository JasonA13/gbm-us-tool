# ICGC
This repository contains the files for a tool to visualise data sourced from the ICGC.


## Links related to the graph
* GBM-US page on ICGC Data Portal https://dcc.icgc.org/projects/GBM-US
* Query for 100 mutations from the ICGC API endpoint https://dcc.icgc.org/api/v1/projects/GBM-US/mutations?field=id,mutation,type,chromosome,start,end&size=100&order=desc


## Data
The API returns the following fields:
* id - mutation id
* type - type of mutation
* chromosome - mutations appear in a chromosome (22 autosome pairs and X / Y)
* start - position in the chromosome at start of mutation
* end - position in the chromosome at end of mutation.
* mutation - mutation
* study - empty field


## Dependencies
Task-specific libraries for the visualisation are included in the repository.
