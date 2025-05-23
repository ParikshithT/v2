---
date: '2'
title: 'IMDB AWS Data Pipeline'
cover: './Amazon.png'
github: 'https://github.com/ParikshithT/AWS_Batch_pipeline'
# external: 'https://halcyon-theme.netlify.com/'
tech:
  - S3
  - Redshift
  - Glue
  - EMR (Spark)
---

The IMDB AWS Data Pipeline project is a full-scale data engineering solution designed to integrate, transform, and analyze user purchase and movie review data within a cloud-native environment. It simulates a real-world analytics pipeline that bridges OLTP data ingestion and unstructured data processing to deliver actionable insights on user behavior.
The pipeline uses AWS services end-to-end — with purchase data ingested into Amazon Redshift via S3 and Redshift Spectrum, and review data staged and processed using AWS EMR and PySpark for text classification. The transformed datasets are then joined in Redshift to create a unified User Behavior Metrics Table, enabling downstream analysis on preferences, engagement, and content effectiveness.
This project demonstrates key data engineering capabilities, including data lakehouse design, SQL optimization, distributed processing, and multi-source data integration. It highlights how AWS tools can be orchestrated to deliver scalable, analytics-ready pipelines that power product insights and customer intelligence.