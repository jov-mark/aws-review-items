# AWS-review-items

AWS big data capstone project. This repo only contains clodformation template that is used for creating resources and loading lambda code from S3 resource bucket.

Application is getting two different streams of data and loads it into S3 buckets. After first batch of items data, EMR cluster is being triggered to process it and find suspicious IP addresses, which are then used to filter upcoming streams. Athena is used for analyzing loaded data. Also Kinesis Analytics is used for analyzing real time stream of data.
