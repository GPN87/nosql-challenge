# nosql-challenge
## Overview
The repository contains two notebooks ('setup_starter' and 'analysis_starter') that interact with a mongoDB database.

**setup.ipynb** loads a json of UK food hygiene data, by establishment, into a MongoDB database using pyMongo.

The database is updated with a new establishment, and it is coded with the correct business ID.

Several find() queries are used to count certain fields.

Geocoordinate data are updated from str to float.

**Analysis.ipynb** exploratory analysis of the establishments collection.

Filters are applied to the collection, and results loaded into pandas DataFrames. Sort, Limit and Regex methods are used to complete filters.

An aggregation pipeline is used to drill down into specific instances of the data, and Pandas DataFrames are created.

## Access and Usage
to clone this repository, use the following command
```
git clone https://github.com/GPN87/nosql-challenge.git
```

