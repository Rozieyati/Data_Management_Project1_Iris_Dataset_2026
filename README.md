# Distributed Data Management Framework for Taxonomic Ingestion via Spark MLlib 

## Academic Report Asset
**Course Project:** STQD6324 Data Management  
**Official Assignment Title:** *An Enterprise Data Infrastructure and Governance Report: Design of Distributed Data Management Pipelines and Schema Governance Using Apache Spark* 

## Project Overview
This repository contains a master-level implementation of a distributed data management pipeline built using Apache Spark (PySpark) on Google Colab. The project focuses on core data management principles, including automated data pipelining, schema enforcement, data quality profiling, and hyperparameter optimization using Grid Search and 5-Fold Cross-Validation.

## Core Data Governance Architecture
1. Pipeline Robustness: Sourced directly via native scikit-learn structures to eliminate external URL vulnerabilities and ensure system uptime.
2. Memory Optimization: Features are consolidated using Spark StringIndexer and VectorAssembler transformers to maximize cluster memory performance.
3. Automated Model Tuning: Deploys ParamGridBuilder and a 5-Fold CrossValidator to mathematically isolate optimal hyperparameter variations.
4. Compliance Controls: Data splitting and cross-validation routines are locked with an explicit seed to guarantee full audit reproducibility.

## Summary of Quality Metrics
The performance metrics recorded on the hold-out testing data partition are:
* Decision Tree Classifier: 0.9821 Accuracy | 0.9821 F1-Score (Selected Deployment Architecture)
* Random Forest Classifier: 0.9643 Accuracy | 0.9643 F1-Score
* Multinomial Logistic Regression: 0.9643 Accuracy | 0.9643 F1-Score
