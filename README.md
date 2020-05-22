# NYC-311-Complaint-Resolution-Predictive-Model-using-Spark
Variables were Agency, complaint type, descriptor, incident zip, incident address, street name, address type, city, facility type, status, resolution description, community board, borough, park facility name, latitude, longitude, created data, closed date. Developed a predictive machine learning Decision Tree regression model using Apache Spark to predict time for an issue to be Resolved. Used AWS Notebook since data size was 5GB. Worked on data cleaning, added seasonality as a factor and trained a model on 70% of data and tested on 30%. Model was off by 12 days which is a good fit considering size of a dataset. Cleaned the data by removing redundant columns, checked overfitting and those with null values. Created Derived Columns to use seasonality factor in model and then trained/tested the model using 70%/30% of the data. Used String Indexer to transform string values in fields to index values. Combined all the columns in to one using VectorAssembler function and passed that column in addition to response column.
