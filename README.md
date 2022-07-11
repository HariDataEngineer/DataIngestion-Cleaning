# DataIngestion-Cleaning

# Create a 3 layer architecture datalake for curating data in the databricks platform

# Three Layers are : Raw Layer, Curated Layer, Serving Layer

# > data-first-note : 
    Follow this to set up the three layers(directories) in databricks file system using 'dbutils'

# > 2_import_data_into_raw_layer :
    Follow this notebook to get the data from web and explore using Spark
    
# > generate_curated_layer : 
    Follow this notebook to get the data from driver node into DBFS file system and apply transformations and data quality checks using spark and store the data in Parquet format into Curated layer from where we will directly send to Serving layer which will be accessible for downstreams for further analysis
