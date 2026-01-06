# Real-Time Crypto Market Data Platform

A production-style data engineering project for real-time cryptocurrency
market data ingestion, processing, and analytics.

## Architecture

CoinGecko API
→ Kafka (KRaft)
→ Spark Structured Streaming
→ Parquet Data Lake
→ PostgreSQL
→ AWS S3 / Redshift (Selective workloads)

## Tech Stack

- Apache Kafka (KRaft mode)
- Apache Spark (Structured Streaming)
- Apache Airflow
- PostgreSQL
- Docker & Docker Compose
- AWS (S3, EC2, Redshift)
- CoinGecko API

## Objectives

- Real-time streaming ingestion
- Fault-tolerant processing
- Cost-efficient hybrid architecture
- Production-grade project structure
