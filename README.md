# Visualisation for Data from the Brain Glioblastoma Multiforme Project (US)
This repository contains the files for an MVP tool to visualise data sourced from the GBM-US. Visualisations on mutation type and chromosomes present the option for filtering on a single option and both attributes  


## Links related to the graph
* **GBM-US page on ICGC Data Portal** https://dcc.icgc.org/projects/GBM-US
* **Query for 100 mutations from the ICGC API endpoint** https://dcc.icgc.org/api/v1/projects/GBM-US/mutations?field=id,mutation,type,chromosome,start,end&size=100&order=desc


## Data
The API returns the following attribute value-pairs:
* **id** - mutation id.
* **type** - type of mutation.
* **chromosome** - mutations appear in a chromosome (22 autosome pairs and X / Y).
* **start** - position in the chromosome at start of mutation.
* **end** - position in the chromosome at end of mutation.
* **mutation** - mutation.
* **study** - empty field.


## Dependencies
Project-specific libraries for the visualisation are included in the repository.


# Additional Steps
Two areas top the list for improvements: 
* **Accessing data directly from the ICGC API endpoint** - Data preparation was undertaken in Python; with additional time, the Fetch API would have been the preferred option for loading data. 
* **Enhancing visual design using D3** - Bar charts are a functional but rudimentary option. The priority is a visualisation for the type overview that can help to detect differences between the minority classes. 
