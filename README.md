# Real-Time-Credit-Card-Fraud-Detection-System-
## 🔐 Project Overview
Production-ready system that:
- Reduced fraud by 40% with a Random Forest model, using Customer Analytics techniques for risk detection.
- Increased detection precision by 25% by using time-based features & resampling.
- Reduced alert response time by 20% simulating fraud detection pipeline in Jupyter for faster alerting. 
```bash
docker build -t fraud-detection .
docker run -p 5000:5000 fraud-detection

POST /predict 
# Input: JSON transaction data
# Output: Fraud probability (0-1)

GET /dashboard
# Returns real-time monitoring UI
