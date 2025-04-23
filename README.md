# UPTEACH: Pediatric Mental Health Support Hub
> A digital platform empowering early detection, streamlined care coordination, and secure data management for pediatric mental health.

## 📘 Overview

**UPTEACH** (Universal Pediatric Telehealth, Education, Assessment & Care Hub) is a comprehensive, scalable platform that enhances pediatric mental health care through advanced screening tools, AI-driven analytics, and secure data management. Built by a multidisciplinary team from **Michigan Technological University**, the project addresses major systemic gaps such as limited provider training, access inequalities, and fragmented care delivery.

This project was developed as part of the Systems Analysis and Design course (SAT 5131) under the mentorship of Professors Daniel Boyle and Guy Hembroff.

## 🎯 Goals

- Consolidate validated screening tools, educational materials, and community services.
- Empower providers with AI/ML-driven diagnostic insights and real-time patient risk assessments.
- Enhance access through a user-friendly interface and telehealth integration.
- Ensure privacy with HIPAA and HITRUST-compliant infrastructure.
- Support underserved areas through a crowdsourced resource mapping system.

## 🧠 Key Features

### 1. Integrated Screening & Analytics
- Tools include: GAD-7, PHQ-9, PSC-17, C-SSRS, Vanderbilt Scale, etc.
- AI models for predicting high-risk cases and recommending interventions.

### 2. Care Coordination Tools
- Automated referral and follow-up workflows.
- Dashboards for provider decision support and patient progress tracking.

### 3. Crowdsourced Resource Mapping
- Real-time updates from community organizations.
- Geolocation filters for region-specific service discovery.

### 4. Security & Compliance
- AES-256 encryption, TLS 1.3, OAuth 2.0, RBAC.
- Regular vulnerability scans and third-party audits.

## 🛠 Technologies Used

- Frontend: React (planned), TailwindCSS
- Backend: Node.js, Express (planned)
- Database: MongoDB / Firebase (scalable options)
- ML Models: Python (scikit-learn, TensorFlow)
- Data Standards: HL7, FHIR for EHR interoperability
- Cloud: AWS/GCP (HIPAA-compliant)

## 📊 Dashboard Insights

Using datasets from Kaggle on youth suicidal behavior and heart disease, UPTEACH visualizes correlations between mental health and physical conditions like BMI and blood pressure—helping identify at-risk children early.

## 🧩 Challenges Addressed

- Misdiagnosis by non-specialist PCPs
- Shortage of child psychiatrists
- Lack of interoperability between systems
- Data privacy concerns in telehealth
- Inconsistent follow-ups in care plans

## 🗺 Future Enhancements

- Full-scale AI integration with predictive modeling
- Expanded multilingual and culturally adapted screening tools
- Seamless EHR interoperability through FHIR APIs
- Mobile apps for caregiver-patient engagement
- Training modules and onboarding resources for clinics

## 👥 Team Members

- Srilekha Nanabala  
- Bridget Nyamekye  
- Benjamin Asomaning  
- Mary Nnipaa Meteku  
- David Blemano

## Link to Google Looker Dashboard
https://lookerstudio.google.com/u/1/reporting/db8f9a65-3cd7-4b57-a63f-88e651c83564/page/cwa0D

## 📚 References & Datasets

- [Suicidal Behavior of Youth Dataset](https://www.kaggle.com/datasets/priya0707/suicidal-behavior-of-youth)  
- [Heart Disease Dataset](https://www.kaggle.com/datasets/denvirgama/heart-disease)  
- The full academic reference list is in the [`docs/`](./docs) folder.

## 📄 License

This project is part of academic coursework and is shared for educational purposes. For reuse or collaboration, please contact the authors or supervising professors.
