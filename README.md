# Data-Engineering-YouTube-Data-Analysis-with-AWS

## Overview
This initiative seeks to implement a secure and efficient system for the organized handling, streamlining, and analysis of structured and semi-structured data from YouTube videos. The focus is on categorizing videos and analyzing trending metrics in a secure manner.

## Project Goals
 1) Data Ingestion Mechanism: Develop a robust mechanism for ingesting data from diverse sources.

 2) ETL System Implementation: Transform raw data into the appropriate format to facilitate effective analysis.

 3) Data Lake Repository: Establish a centralized repository in the form of a data lake to store information obtained from multiple sources.

 4) Scalability Assurance: Ensure the scalability of the system to accommodate growing data volumes seamlessly.

 5) Cloud Integration (AWS): Leverage cloud computing, specifically AWS, for processing vast amounts of data, as local computers may be insufficient for such tasks.

 6) Reporting Dashboard: Construct a comprehensive dashboard to obtain insights and answers to the questions posed during analysis.

## Services we will be using

#### 1) Amazon S3:
Function: Object storage service.
Features: Manufacturing scalability, data availability, security, and performance.

#### 2) AWS IAM:
Manage access to AWS services and resources securely.

#### 3) Amazon QuickSight:
Facilitates cloud-based business intelligence with scalable and machine learning capabilities.

#### 4) AWS Glue:
Simplifies data discovery, preparation, and combination for analytics, machine learning, and application development.

#### 5) AWS Lambda:
Enables running code without the need for server creation or management.

#### 6) Amazon Athena:
Allows querying data directly in S3 without the necessity of loading it, making it a serverless and efficient solution.


## Dataset Used
The Kaggle dataset comprises daily statistics in CSV files documenting popular YouTube videos across several months. Each day witnesses the publication of up to 200 trending videos across various locations, with each region having its dedicated file. The dataset encompasses details such as video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count. Additionally, a category_id field, varying by region, is present in the linked JSON file corresponding to each area. This dataset thus offers comprehensive insights into the dynamics and attributes of trending YouTube videos across diverse regions over an extended timeframe.

#### https://www.kaggle.com/datasets/datasnaek/youtube-new




