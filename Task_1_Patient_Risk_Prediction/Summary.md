# Problem Title
Patient Readmission Risk Prediction

## Problem Description
Hospitals struggle with high patient readmission rates, delayed medical intervention, and manual patient monitoring. 
Target users are doctors and hospital administrators who need early risk insights to plan timely interventions.

## Proposed AI/ML Solution
An ML-based risk prediction model using **Random Forest / XGBoost** trained on patient demographics, vitals, and lab results.  
Preprocessing includes handling missing values, normalization, and encoding.

**Workflow:**  
Data → EDA and Preprocessing → Model Training (SageMaker/Azure ML) → Risk Scoring → Dashboard

## Cloud & Tech Stack
- **Data Storage:** AWS S3 / Azure Blob  
- **Model Training:** AWS SageMaker / Azure ML  
- **Database:** AWS RDS / Firestore  
- **Deployment:** Flask or Streamlit API  
- **Monitoring:** AWS CloudWatch / Stackdriver  

## Expected Outcome / Impact
- Early intervention to prevent readmission  
- Automated, accurate risk prediction  
- Improved healthcare efficiency & patient care quality  

## Architecture Diagram
Refer to [Architecture Diagram](Task_1_Patient_Risk_Prediction/architecture.mermaid)

## Optional Notes
Dataset includes patient history, vitals, lab results, and diagnosis codes.
