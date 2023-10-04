# BigQuery xml parse
Project bigquery-xml-jpk


# Google create bucket
```
gcloud storage buckets create gs://xml-jpk-bucket

gcloud storage buckets create gs://xml-jpk-bucket --project=bigquery-xml-jpk --default-storage-class=NEARLINE --location=US-EAST1. --uniform-bucket-level-access
```

# Storage
## external data
https://cloud.google.com/bigquery/docs/external-table-definition

## import Data 

https://cloud.google.com/bigquery/docs/loading-data-cloud-storage-json#sql
