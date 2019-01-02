
# Data science with Google Cloud

https://www.datacamp.com/community/tutorials/google-cloud-data-science

https://bigquery.cloud.google.com/

### BigQuery resources

* [BigQuery cookbook](https://support.google.com/analytics/answer/4419694)
* [BigQuery Public datasets](https://cloud.google.com/bigquery/public-data/)

### Exploring and Preparing your Data with BigQuery and DataPrep

Notes for https://www.coursera.org/learn/gcp-exploring-preparing-data-bigquery/

1. Create new data set - name it ecommerce

2. Run following query (should import one day worth of data into you the data set from above)
#standardSQL
CREATE OR REPLACE TABLE ecommerce.all_sessions_raw_dataprep
OPTIONS(
  description="Raw data from analyst team to ingest into Cloud Dataprep"
) AS
SELECT * FROM `data-to-insights.ecommerce.all_sessions_raw` 
WHERE date = '20170801'; #limiting to one day of data 56k row for this lab

3. 
Go to DataPrep -> BigQuery -> ecommerce 
You should see the data from the import in there

https://support.google.com/analytics/answer/3437719?hl=en

### Visualizing BigQuery Data

* [Google Data Studio](https://cloud.google.com/bigquery/docs/visualize-data-studio)
* [Jupyter Notebook](https://cloud.google.com/bigquery/docs/visualize-jupyter)


