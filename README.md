# AWS-IoT-Assignment
A0206632M EE5111 Assignment 1 Python Coding
This report shows the implementation of using a Raspberry Pi 3 hardware sending signals to AWS IoT Core, which is stored captured in non SQL database service called DynamoDB. The raw form of data could be stored in Amazon simple storage service S3 via data pipeline. This could be further processed via AWS Glue crawlers, into AWS Glue Data Catalog that could transform (Glue ETL) to better format and output to Amazon quicksight or other tools for visualisation.  
Note: the problem of “AWSIoTPythonSDK” not found can be resolved by saving the entire “AWSIoTPythonSDK” folder into the same working folder. my case: myfolder.
