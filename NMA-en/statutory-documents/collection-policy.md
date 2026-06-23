# NMD Collection policy

National Metadata Directory aggregates metadata records of scientific datasets from Czech research. It contains information on research data of all disciplines, from natural sciences and engineering as well as social sciences and humanities. 

The National Metadata Directory concentrates metadata on datasets mainly from the [National Repository Platform (NRP)](https://docs.nrp.eosc.cz/en/docs/overview) repositories and selected international repositories with Czech participation. However, it does not contain records of scientific articles and scientific texts, which can be found in the [National Repository for documents](https://docs.narodni-repozitar.cz). 

Read more on general aim of metadata directory in [NMD Mission statement](./repository-mission.md).

## Overview of current data sources

Current data sources: National Metadata Directory currrently harvests from three data sources, each comprising datasets from multiple institutions.

- National Repository Platform Catch-all Data Repository (all records in OAI endpoint)

- LINDAT/CLARIN Repository (all records in OAI endpoint)
  
- Academy of Sciences repository (all dataset records in OAI endpoint)

- Zenodo (as non-NRP repository only selection of organizations and resource types covering datasets)

- Individual direct input for the purpose of reporting dataset in the national Register of Research Results

### Institutions represented

There are datasets from multiple institutions in each of the above data sources. The LINDAT Repository contains datasets mainly from UFAL and other organisations, directly submitted as primary recors into LINDAT Repository, not harvested by LINDAT from third party repositories (LINDAT Catalog).

The datasets from Zenodo are selected from the datasets of VŠCHT, ČVUT, ZČU, UPOL and UTB universities, based on different variants of the institution name. Currently, the exact affiliation of records to an institution is not accurate unless the record publisher is filled in correctly. Records are in English without mapping to any Czech equivalents.

### Harvest period and schedule

All harvest sources are periodically re-harvested, updating the older records with newly acquired metadata, matching the records by the same identifier. Periodicity of each repository harverst depends on overall schedule, number of records, source repository accepted workload rates and can range from one week to one month. Requests for immediate priority of the source repository re-harvest, for access to harvest resutlts dashboard or for adding a new repository to harvest can be submitted by publishers to NMA support.

## Typology of content

The National Metadata Directory focuses on research datasets and additional research material, except articles and other document types. The following is a selection from COAR resource types vocabulary applicable to metadata records:

| datasets, software | other |
|---|---|
|<code><ul><li>dataset</li><ul><li>aggregated data</li><li>clinical trial data</li><li>compiled data</li><li>encoded data</li><li>experimental data</li><li>genomic data</li><li>geospatial data</li><li>laboratory notebook</li><li>measurement and test data</li><li>observational data</li><li>recorded data</li><li>simulation data</li><li>survey data</li></ul><li>software</li><ul><li>research software</li><li>source code</li></ul></ul></code>|<code><ul><li>cartographic material</li><ul><li>map</li></ul><li>design</li><ul><li>industrial design</li><li>layout design</li></ul><li>image</li><ul><li>moving image</li><ul><li>video</li></ul><li>still image</li></ul><li>interactive resource</li><ul><li>website</li></ul><li>knowledge organization system</li><li>learning object</li><li>sound</li><ul><li>musical composition</li></ul><li>manuscript</li><li>musical notation</li></ul></code>|

## Content selection and record priority criteria

For National Repository platform, National Metadata Directory does not make any selection of records from harvested repositories based on record metadata. The only criteria to accept records is source repository status as National Repository Platform data repository in National Repository Catalogue. Then, all records exposed by their published OAI interface are harvested and selection of recods for the harvest depends on the source repository curatorial decision. Czech affiliation is assumed for all the records as the repository is considered to be original publisher of the records. The above applies accordingly also for individual direct input of records for reporting in Czech national Register of Research Results.

When harvesting from other than NRP repositories and generalist repositories, selection of OAI published records is made to match NMA collection policy and mission statement in regard to Czech-affiliated science and dataset resource types.

In the case of a record appearing in multiple harvested repositories with the same persistent identifier, the metadata from the newer harvest or priority source are then used to update the record. Priority of the source repository can be designated by publisher upon NMA support request. The harvested records provided with different persistent identifiers, though possibly referencing the same original dataset, are not being merged or updated with metadata from record with different PID.

## File Format Registry

Only metadata records are collected, thus no file format registry is maintained by National Metadata Directory. For data files of records, links to the source repositories are displayed, where the files can be downloaded and file format interpretation consulted.


