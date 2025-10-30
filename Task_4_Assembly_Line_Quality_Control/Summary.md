# Problem Title
AI-Powered Quality Control for Manufacturing

## Problem Description
Manual defect inspection is slow, inconsistent, and error-prone, reducing production quality.  
Target users: factory quality engineers and automation teams.

## Proposed AI/ML Solution
A **CNN or YOLO-based defect detection system** using camera feeds from the assembly line.  
Preprocessing: Image filtering, normalization.

**Workflow:** Camera → Cloud → Model Training → Edge Deployment → Dashboard

## Cloud & Tech Stack
- **Storage:** AWS S3 / Azure Blob  
- **Training:** AWS SageMaker / Azure ML  
- **Edge Deployment:** Factory robot / IoT device  
- **Monitoring:** CloudWatch / Azure Monitor  
- **Dashboard:** Streamlit / Flask  

## Expected Outcome / Impact
- Instant defect detection  
- Improved quality consistency  
- Reduced waste and downtime  

## Architecture Diagram
Refer to [Architecture Diagram](architecture.mermaid)

## Optional Notes
Dataset: Product images labeled as Defective / Non-defective.
