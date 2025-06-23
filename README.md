Customer Churn Prediction Dashboard
This project helps identify bank customers who are likely to churn using a machine learning model built with XGBoost. It includes a complete pipeline from data preprocessing to prediction and visualization using Streamlit and Python.

├── data/
│   ├── raw/                   # Raw customer data
│   ├── processed/             # Cleaned data used for training/prediction
│   └── predictions/           # Output churn predictions
│
├── models/
│   ├── churn_xgb_model.pkl         # Trained model (XGBoost)
│   └── preprocessing_pipeline.pkl  # Encoders & scalers used in prediction
│
├── scripts/
│   ├── preprocess.py               # Preprocessing logic
│   ├── predict_batch.py            # Run batch predictions on new data
│   └── retrain_model.py            # (Optional) Script to retrain the model
│
├── churn_dashboard.py         # 📊 Streamlit dashboard for stakeholders
├── requirements.txt           # Python dependencies
└── README.md
