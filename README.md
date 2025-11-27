# Final Capstone Project: Retail + Media Analytics Platform

## Overview
A full-scale data engineering platform featuring:
- Kafka real-time ingestion  
- Spark batch + streaming  
- S3/ADLS storage  
- Delta Lake / Snowflake  
- Airflow orchestration  
- Terraform provisioning  

## Architecture Diagram
(Insert your PNG from /docs)

## Pipeline Flow
api → kafka → spark → delta → snowflake → looker/tableau

## How to Run Locally
docker-compose build  
docker-compose up

## Deployment  
Terraform scripts included for AWS/GCP.

