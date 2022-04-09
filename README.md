# bid_data_challenge

In this challenge we used PySpark to do ETL to two different datasets contained in s3 buckets, we chose Electronics and Video Games datasets in this case. During the ETL process we pulled the data from the S3 buckets using Google Collab and PySpark, we made sure to drop null and duplicate values. We then proceeded to generate the necessary dataframes to match the SQL schema and at last we set the configuration to push the dataframes to AWS.
