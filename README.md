# Energy Anomaly Detector

Real-time energy consumption anomaly detection system built on 2GB+ of real IoT sensor data.

## Problem
Abnormal energy consumption patterns - caused by equipment faults, energy theft,
or sensor failures - cost utilities millions annually. This system detects them automatically
and explains WHY each reading is anomalous.

## Planned Tech Stack
- **ML:** Isolation Forest + XGBoost + SHAP explainability
- **Tracking:** MLflow experiment tracking
- **API:** FastAPI
- **Dashboard:** Streamlit
- **Deployment:** Docker + AWS (EC2 + S3 + ECR + ALB + CloudWatch)
- **Dataset:** UCI Individual Household Electric Power Consumption (2GB, 9M rows)

## Project Status
🚧 In progress

## Structure