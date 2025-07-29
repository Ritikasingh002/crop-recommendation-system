# 🌾 Crop Recommendation System with IBM Watsonx.ai Studio

A supervised ML model built using IBM Cloud’s AutoAI to recommend suitable crops based on soil and climate data. Developed as part of Week 2 of the IBM AI & Cloud internship with Edunet Foundation, supported by AICTE.

🔍 Objective
Suggest the best crop based on parameters like nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, soil pH, and rainfall.

🧪 Dataset
Uses an India-specific "Crop Recommendation Dataset" enriched with rainfall, climate, and fertilizer data.

🧠 Tech Stack
- IBM Cloud
- Watsonx.ai Studio + AutoAI
- IBM Cloud Object Storage
  
⚙️ Workflow Summary
- Setup: Created project & runtime in IBM Watsonx.ai Studio.
- Modeling: Used AutoAI to train on Crop_recommendation.csv; predicted label using multiclass classification.
- Evaluation: LGBM Classifier chosen with 99.1% accuracy.
- Deployment: Model deployed as an online service named Crop_Recommendation.
- Testing: Real-time prediction returned "chickpea" with 99% confidence.
  
✅ Outcome
High-accuracy model successfully deployed for real-time crop prediction.
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/6c27ddea-371b-4354-b703-cc712006004f" />

🙌 Acknowledgments
Thanks to Edunet Foundation and AICTE for the opportunity to work on this hands-on AI project.


