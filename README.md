# Predictive Maintenance Implementation

## Overview
This project implements a data pipeline and machine learning model for predictive maintenance. It leverages a medallion architecture with Delta Lake for data storage, PySpark for data processing, MLflow for model tracking and experimentation, and FastAPI for serving the trained model via a REST API.

## Features
- **Data Processing**: Uses PySpark for scalable data processing and transformation.
- **Medallion Architecture**: Organizes data into bronze, silver, and gold layers using Delta Lake.
- **Model Tracking**: Tracks experiments and models with MLflow.
- **Model Serving**: Deploys the trained model as a REST API using FastAPI.

## Dataset
The dataset used in this project is sourced from Kaggle:  
[Machine Predictive Maintenance Classification](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

## Setup

### Prerequisites
- Python 3.8 or higher
- Java 8 or higher (required for PySpark)
- MLflow tracking server (optional, for experiment tracking)
- Git (for cloning the repository)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
