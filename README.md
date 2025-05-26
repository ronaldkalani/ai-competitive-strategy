
# AI-Driven Competitive Strategy Optimization

This project explores how AI and machine learning can power **competitive intelligence**, **temporal demand forecasting**, and **causal inference** using real-world datasets from Airbnb, Uber, and marketing campaigns.

---

## Project Summary

This dashboard and analysis pipeline:
- Analyzes **Airbnb listings** to extract pricing strategy and platform competition.
- Models **Uber pickup trends** using time-series and clustering techniques.
- Performs **causal inference** on marketing campaign data to estimate conversion uplift.
- Simulates business decisions with statistical modeling and data visualization.

---

## Goal

To demonstrate how AI/ML techniques can be applied across different domains to:
- Optimize pricing
- Allocate resources effectively
- Evaluate campaign impact using causal frameworks

---

## Intended Audience

- Data Scientists
- Product Managers
- Marketplace Analysts (Airbnb/Uber-style platforms)
- Marketing & Growth Strategists

---

## Datasets

| Dataset                | Description                                       |
|------------------------|---------------------------------------------------|
| `AB_NYC_2019.csv`      | Airbnb NYC listing data with pricing and demand   |
| `uber-raw-data-*.csv`  | Uber FOIL pickup data from NYC                   |
| `marketing_AB.csv`     | Simulated A/B marketing experiment (conversion)   |

---

## Key Features

### Competitive Intelligence (Airbnb)
- Price & availability analysis by borough and room type
- Top-performing neighborhoods by average price
- Supply vs demand proxy using review counts

### Large-Scale Temporal Analysis (Uber)
- Demand pattern by hour and weekday
- Geospatial clustering of pickup hotspots (K-Means)
- Rush hour simulation and weather impact analysis

### Causal Inference (Marketing)
- Propensity score modeling using logistic regression
- A/B testing and Weighted Average Treatment Effect (ATE)
- Business insights on whether to scale/stop campaigns

---

## ⚙Setup Instructions

1. Clone or download this repository.
2. Ensure the following files exist:
   - `app.py`
   - `marketing_AB.csv`
   - `AB_NYC_2019.csv`
   - (optional) `uber-raw-data-*.csv`

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the Streamlit dashboard:
```bash
streamlit run app.py
```

---

##  Conceptual Enhancement: AGI Perspective

This project can be extended toward **Artificial General Intelligence (AGI)** by:
- Creating an autonomous agent that reasons across marketing, mobility, and housing markets
- Simulating multi-agent platforms where agents dynamically adapt pricing, logistics, and engagement strategies

---

## References

- Airbnb NYC Data: https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data
- Uber Pickup Data: https://github.com/fivethirtyeight/uber-tlc-foil-response
- Causal Inference Handbook: https://matheusfacure.github.io/python-causality-handbook/

---

## Author

**Ronald Kalani**  
 ronaldkalani@yahoo.ca  
[LinkedIn](https://www.linkedin.com/in/ronald-kalani-1a465533)

---
