# DAF - Data Management
This repo describes the philosophy behind the data management architecture of the Data & Analytics Framework (DAF). In particular, we'll describe the following topics:
- Data Structure
- Ingestion
- Re-distribution

## Overview: Data in DAF
Dataset in DAF are of three types: standard, ordinary and raw. **Standard datasets** are defined as datasets with national relevance, standardized across data sources (there may be multiple data sources describing the same phenomena, i.e. the bike sharing phenomena can have a data source from "Comune di Milano", another from "Comune di Torino", etc.) and supported by the highest level of information/metadata. They are aimed at describing phenomena that are common nationwide and therefore are based on a detailed set of rules and standardization mechanisms that will make them homogeneous.

**Ordinary datasets** have "owner" relevance, in the sense that they are defined and generated by a specific owner for its specific usage. They do not obey to a standard nationwide schema, but the owner needs to specify metadata and info about the dataset before ingesting the data into the platform.

**Raw datasets** are those with the lowest level of information: DAF works more as a storage layer with simple look up mechanism via rest API. They are mostly used to manage Open Data without stringent metadata information.

## Where to go from here
We advise you read all .md file in the root of this repository to get the full flavor of data management in DAF. In particular, we'd suggest the following order:
1. [tbd]s