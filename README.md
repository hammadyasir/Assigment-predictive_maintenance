# Predictive Maintenance Implementation

## Overview
This project implements a data pipeline and machine learning model for predictive maintenance. It leverages a medallion architecture with Delta Lake for data storage, PySpark for data processing, MLflow for model tracking and experimentation, and FastAPI for serving the trained model via a REST API.

## Project Structure
The repository is organized as follows:

predictive_maintenance_project/
├── 📁 Documentation/
│ ├── 📄 Architecture_Diagram.pdf # System design diagrams
│ ├── 📄 Data_Modeling_Document.pdf # Silver and Gold layer data models
├── 📁 Code/
│ ├── 📄 api.py # FastAPI implementation for model serving
│ ├── 📄 Predictive_Maintenance_Pipeline.py # PySpark data pipeline
│ ├── 📄 requirements.txt # Project dependencies
├── 📄 README.md # Setup and usage instructions


## Features
- **Data Processing**: Utilizes PySpark for scalable data processing and transformation
- **Medallion Architecture**: Organizes data into Bronze, Silver, and Gold layers using Delta Lake
- **Model Tracking**: Tracks experiments and models using MLflow
- **Model Serving**: Deploys the trained model as a REST API using FastAPI

## Dataset
The dataset used in this project is sourced from Kaggle:  
[Machine Predictive Maintenance Classification](https://www.kaggle.com/datasets/datasets)

## Setup

### Prerequisites
- Python 3.8 or higher
- Java 8 or higher (required for PySpark)
- MLflow tracking server (optional, for experiment tracking)
- Git (for cloning the repository)

### Installation
1. Clone the repository:
```bash
git clone git@github.com:hammadyasir/Assignment-predictive_maintenance.git
cd Assignment-predictive_maintenance

2. Install dependencies:
pip install -r Code/requirements.txt

### Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements or bug fixes.
