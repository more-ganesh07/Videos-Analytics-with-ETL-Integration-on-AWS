## Data Engineering YouTube Analysis with AWS

### Overview:
This repository focuses on securely managing, streamlining, and analyzing structured and semi-structured YouTube video data, with a specific emphasis on video categories and trending metrics.

### Project Goals:
 1) Data Ingestion: Develop a mechanism for ingesting data from diverse sources
 2) ETL System: Transform raw data into the appropriate format.
 3) Data Lake: Establish a centralized repository for storing data from multiple sources.
 4) Scalability: Ensure the system scales seamlessly with increasing data size.
 5) Cloud Integration (AWS): Utilize AWS for processing large amounts of data.
 6) Reporting Dashboard: Build a dashboard to extract insights from the data.


### Services Used:
1) Amazon S3: Object storage service offering manufacturing scalability, data availability, security, and performance.
2) AWS IAM: Identity and access management for secure access to AWS services and resources.
3) QuickSight: Scalable, serverless, embeddable, machine learning-powered BI service for cloud-based business intelligence.
4) AWS Glue: Serverless data integration service facilitating data discovery, preparation, and combination for analytics and application development.
5) AWS Lambda: Computing service enabling code execution without server management.
6) AWS Athena: Interactive query service for S3, allowing data querying without the need to load it.

### Dataset:
The repository includes a Kaggle dataset containing daily statistics (CSV files) of up to 200 trending YouTube videos across multiple months and locations. Each region has its file, including video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. The associated JSON file contains a region-specific category_id field. This dataset serves as a comprehensive source for understanding the dynamics of trending YouTube videos. 

https://www.kaggle.com/datasets/datasnaek/youtube-new



