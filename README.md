# Customer Service Response Time Predictor

![Project Visualization](reports/figures/response_time_distribution.png) <!-- Add a main image -->

## Project Overview
Predictive modeling system analyzing 300k+ customer service requests to forecast resolution times using Random Forest regression.

**Key Features:**
- Comprehensive EDA of service request patterns
- Feature engineering including time-to-resolution metrics
- Machine learning pipeline with Random Forest
- Interactive visualizations of results

## Technologies Used
- Python 3.8+
- Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn
- Jupyter Notebook

## Results
Model achieved **R² score of 0.85** and **MAE of 2.3 hours** in predicting response times.

Top predictive features:
1. Complaint type
2. Borough location
3. Time of submission

## Installation
```bash
git clone https://github.com/yourusername/customer-service-response-predictor.git
cd customer-service-response-predictor
pip install -r requirements.txt
