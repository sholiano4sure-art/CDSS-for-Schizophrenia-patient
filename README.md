**Clinical Decision Support System For Shizophrenia**

This project presents a machine learning based clinjical Decision Support System(CDSS) designed to support schizophrenia diagnosis. 
The System integrates EEG signal features with synthetic Electronic Health Record(EHR) data to provide accurate, data driven predictions.
A shiny web Application was develop to stimulate real world clinical usage, allowing users to select patient records and recieve instant 
predictions.

**Dataset**
- EEG Data:Brain signal recordings (Healthy vs. Schizophrenia)
- Age
- Gender
- Symptom severity
- Treatment
- 
**Methods**
  - Feature extraction: time domain and frequency domain EEG feature
  - Data Integration: EEG + EHR
  - Models: Randdom forest, SVM, Logistic Regression, Decision Tree, XGBoost
  - Evaluation: 5 fold cross validation, accuracy, ROC-AUC
  
  **Results**
    - Best models: XGBoost
    - Accuracy: ~91-92%
    - improved performance using multimodal data
    
    **CDSS App**
      - Built with **R shiny**
      - select patient - automatic prediction
      - Output: Healthy / schizophrenia
    
      
