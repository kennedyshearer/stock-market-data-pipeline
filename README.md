# Real-Time Stock Market Data Analytics Pipeline

<p align="center">
  <img src="https://i.gyazo.com/3194b661e8a109bcfeb1e7ee655aa7c8.png" alt="Diagram" width="700">
  <br>
  <sub>Figure 1: Architecture Diagram</sub>
</p>

## Overview
This project builds a real-time analytics pipeline for stock market data using AWS serverless and event-driven services. It ingests, processes, stores, and analyzes stock data in real-time, generating actionable insights for investors and analysts. The pipeline demonstrates scalable, low-latency, and cost-efficient cloud analytics.

## Problem Statement
Batch processing of stock data delays insights and prevents timely decision-making. Traditional monitoring cannot detect anomalies or trends in real-time. The challenge was to create a scalable, serverless system capable of ingesting high-volume streams, processing data instantly, storing results, and sending actionable alerts.

## Solution
- Amazon Kinesis ingests real-time stock data streams  
- AWS Lambda processes data, detects trends, and performs transformations  
- Amazon DynamoDB stores structured, low-latency stock data  
- Amazon S3 + Athena enables historical analysis  
- Amazon SNS sends real-time alerts (Email/SMS) for stock trends  
- IAM Roles ensure secure service integration

![Workflow / Implementation Placeholder](images/workflow.png)

## Steps to be Performed 👩‍💻
1. Setup Data Streaming with Amazon Kinesis  
2. Process Data with AWS Lambda  
3. Query Historical Data using Athena  
4. Send Stock Trend Alerts via SNS  

## Key Services / Tools Used 🛠
- Amazon Kinesis Data Streams [Streaming]  
- AWS Lambda [Compute / Processing]  
- Amazon DynamoDB [Database]  
- Amazon S3 [Storage]  
- Amazon Athena [Analytics]  
- Amazon SNS [Notifications]  
- IAM Roles & Policies [Security]  

## Results

  <p align="center">
  <img src="https://i.gyazo.com/b85a24fe5269a02b29dd302be1b1db53.png" alt="Application" width="700">
  <br>
  <sub>Figure 3: Application</sub>
</p>

## Future Improvements
- Integrate advanced anomaly detection using ML models  
- Visualize trends using QuickSight dashboards  
- Implement user-configurable alert thresholds  
