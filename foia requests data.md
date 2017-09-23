# FOIA Metadata: Storage and Presentation

This document outlines a few suggestions for improving the storage and presentation of FOIA requests data and the datasets obtained from the government in response to FOIA requests.

Currently, the requests data are accessible by clicking through "Requests"-->"Browse all requests". The datasets 

Place based information is readily accessible through the "Jurisdiction" filter, although this should probably be renamed "Location".

Thematic (or "issue-based" information) is currently very difficult to access. I tried a few different searches for "health", but was unable to filter down to access requests that were just health-related.

## Effective metadata storage

CKAN, an open data platform, powers most open data platforms on the web, including the US government's open data platform - catalog.data.gov. Data.gov hosts several disparate datasets (much like MuckRock) but organizes them by:

1. Topic
2. Topic categories
3. Dataset type
4. Tags
5. Data Format
6. Organization type
7. Organization
8. Publisher
9. Bureau

The metadata for these are "harvested" from external websites, as explained here: https://www.data.gov/developers/harvesting. As part of "Project Open Data", government offices follow an open metadata scheme, described here: https://project-open-data.cio.gov/v1.1/schema/

The datasets hosted by MuckRock could be better organized to adhere to a well-defined metadata schema similar to the one specified by Project Open Data. 


## Presentation
The following filters can be added to increase accessibility, although this presentation step is dependent upon appropriate storage of the extra metadata required:
1. Topic
2. Dataset type (spatial / non-spatial)
3. Data format (CSV, PDF, JPG, etc.)

Further, one immediate improvement that can be made is dynamic updation of dropdown options - for example, if I filter by jurisdiction "Massachusetts", when I use the dropdown for "agencies", agencies in other states should not be displayed as an option. This makes searching for and filtering data a lot easier.


