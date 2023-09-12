# Data-Pipeline-for-Translation-Memory
Designing and implementing a simple data pipeline to extract, transform, and load  (ETL) data from a Translation Memory exchange (TMX).The TMX file  contains parallel translation between English and Arabic.

## Data Pipeline
A data pipeline is a method in which raw data is ingested from various data sources and then ported to data store, like a data lake or data warehouse, for analysis. Before data flows into a data repository, it usually undergoes some data processing. This is inclusive of data transformations, such as filtering, masking, and aggregations, which ensure appropriate data integration and standardization. This is particularly important when the destination for the dataset is a relational database.

 ## Prerequisites
 Download the TMX dataset and open it as TXT file and upload or share the file path when using it in python.
 TMX (Translation Memory Exchange) is a file format used in the translation industry to exchange data between different localization tools. TMX files are XML-based and follow 
 standardization, allowing the sharing of translation memory data across various platforms and tools.

 ## Steps
 The data from the TMX file is extracted and stored in a pandas DataFrame.
 For connecting  the dataset to a relational database use the necessary module, connect and store the  parallel translation between  English and Arabic.

 ## Conculsion
 Extracted the data from the TMX file and transformed it into source and target column and stored it in a dataframe.
 Connected the raw data with MYSQL database and the data flows to the data repository in the database.
 
 
 
 
