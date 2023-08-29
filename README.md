# Agricultural Data

## Overview


The list of agricultural data sources is focused on those that contain data about imported food inspection; primarily animals and animal products.  

There may be cases where the data source is not directly applicable, for example domestic meat inspection.  These are included for possible future use or to find similar data sources in the future that better fit our needs.

## GAIN Reports

[https://gain.fas.usda.gov/#/](https://gain.fas.usda.gov/#/)


This is primarily human readable text reports, so it is  difficult to use as a primary data source source.  This may be a good source for any public alerts that are issued; using AI to parse these should be possible.

Note: The search functionality works in the above site.

## FSIS Data
The FSIS sites contains inpsection data, but seems to be domestic only.

[https://www.fsis.usda.gov/science-data/data-sets-visualizations/laboratory-sampling-data](https://www.fsis.usda.gov/science-data/data-sets-visualizations/laboratory-sampling-data)

See the snippet in examples/RawPoultrySampleDataset.md, or the raw data in examples/RawPoultrySampleDataset.csv






## Economic Research Service Data APIs

[https://www.ers.usda.gov/developer/data-apis/](https://www.ers.usda.gov/developer/data-apis/)

This appears to be domestic data only, with no inspection data.  But we need to examine the APIs to verify.

I have obtained a key for these APIs, it was easy to obtain.  We should have each person get their own key.  I have verified that the REST and GraphQL APIs both work, but have only taken a very quick look at the data, it does not seem applicable upon cursory inspection.

### Description of the API

From [here](https://www.ers.usda.gov/developer/data-apis/arms-data-api/)

ARMS Data API
1. Introduction
USDA’s Economic Research Service (ERS) is making data from USDA’s Agricultural Resource Management Survey (ARMS) available through an Application Programming Interface (API) to better serve customers. The data in the API are available in JSON format and provide attribute-based querying. The data are also available in bulk files.
This documentation provides a brief explanation of the API to get you started. For user convenience, we provide demos using R: open source statistical programming language.
A list of variables, by report, is provided in section 3. An exhaustive list of all variables and detailed descriptions is found in the file AllVariables.csv.
2. Getting Started with the API
You may use the ARMS Data API to develop a service to search, display, analyze, retrieve, view, and otherwise "get" information from ARMS data.
2.1 Registration
Users of the ARMS data API are required to sign up for an API key using the form provided by api.data.gov below, a free API management service for Federal agencies. A valid email address is required to obtain a key. Once users have completed the signup requirements, the API key will be automatically sent to the user-provided email address. API keys provide a means to notify users of changes in the APIs.




