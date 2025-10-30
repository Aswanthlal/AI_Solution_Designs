# Problem Title
AI Chatbot for Patient Assistance & Appointment Scheduling

## Problem Description
Patients experience delays in getting responses and difficulty in booking appointments.  
Target users are patients and hospital front-desk staff.

## Proposed AI/ML Solution
Conversational AI using **BERT / Rasa** integrated with **AWS Lex / Dialogflow**.  
Preprocessing: Text cleaning, intent tagging, and response mapping.

**Workflow:** User Query → Chatbot → NLP Model → Response / Appointment Booking

## Cloud & Tech Stack
- **Chatbot Framework:** AWS Lex / Dialogflow  
- **Model Logic:** BERT / Rasa + AWS Lambda  
- **Database:** AWS DynamoDB / Firestore  
- **Frontend:** Web / Mobile app  
- **Monitoring:** CloudWatch / Dialogflow Analytics  

## Expected Outcome / Impact
- 24/7 instant patient assistance  
- Automated scheduling and FAQs  
- Improved patient engagement and satisfaction  

## Architecture Diagram
Refer to [Architecture Diagram](architecture.mermaid)

## Optional Notes
Dataset: Hospital FAQs, chat history, appointment records.
