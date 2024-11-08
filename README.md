# Spotify-End-to-End-Data-Engineering

## Setting Up AWS Environment
1. Create an IAM user with the necessary permissions (S3, Glue, Athena, QuicksightAthena, QuickSightDescribeRDS)
2. Setup S3 Buckets
3. Transform using Glue


### S3 Buckets Setup
Create an S3 bucket with two folders, "staging" and "datawarehouse".

Upload the three csv files into the staging foler

### Use AWS Glue to transform data and move into datawarehouse
