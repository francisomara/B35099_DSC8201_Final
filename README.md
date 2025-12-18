# B35099_DSC8201_Final
├── data/
│   ├── raw/
│   ├── processed/
│   └── Francis.csv
├── notebooks/
│   ├── PartA_CRISPDM.ipynb
│   └── PartB_Modeling.ipynb
├── models/
│   └── bugisu_heavy_rain_rf.pkl
├── api/
│   ├── app.py
│   └── Dockerfile
├── mlruns/
├── README.md
└── requirements.txt

## Key Components
- **Distributed Pipeline:** Spark/Dask for ingestion and feature engineering  
- **Machine Learning Models:** Logistic Regression, Random Forest, DNN  
- **Experiment Tracking:** MLflow  
- **Deployment:** FastAPI + Docker  
- **Monitoring:** Data drift, model drift, CI/CD design  

## How to Run
1. Install dependencies:
pip install -r requirements.txt
   
3. Run the API:
uvicorn app:app --reload

3. Access documentation:
http://localhost:8000/docs


## Results
- Random Forest achieved the best performance.
- SHAP identified rainfall lags and seasonal indicators as key predictors.

## Ethical Considerations
- No personal data used.
- Compliance with Uganda Data Protection Act & GDPR.
- Transparent model interpretation via SHAP.

## Author
Francis — MSc Data Science, Uganda Christian University.



http://localhost:8000/docs
