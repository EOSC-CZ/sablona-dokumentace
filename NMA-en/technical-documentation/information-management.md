
# Information management

This document describes requisities of information management, for general guide how to search and use citation see [Guide for communities](../guides/for-communities.md)

# Data discovery

General ways to discover the data in National Metadata Directory are search and browse interfaces as part of the web application. Results can be further refined by user interface facets for selecting certain metadata criteria.

All metadata are machine harvested from source repositories. Procedures ensuring quality of data, FAIR-ification, conformation to metadata standards are on behalf of source repositories and National Metadata Directory does not apply any additional data quality policies except necessary formal validation of harvesting metadata format. 

# Data identification

Persistent identifiers are assigned by source repositories, National Metadata Directory is PID scheme agnostic and can store and display records of any PID scheme, although currently present are two schemes: DOI and Handle. Persistent URLs are provided for every PID, linking to registered original record.

**In record detail**, the dataset PID and scheme is displayed on the right labeled "Dataset Identifiers" with the link to the original record: 

![Repository interface - record detail header](../images/record_detail_header.png "Repository interface - record detail header")

# Technically, where the records come from?

For harvest source identification, please use Export in JSON format function on Record detail page and navigate to "oai" block, where the harvest URL ad date of record acquisition are displayed:
   
![Export JSON - OAI source](../images/export_json_oai.png "Export JSON - OAI source")
