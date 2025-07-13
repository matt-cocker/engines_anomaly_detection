# Engine Anomaly Detection with Unsupervised Learning

This project uses unsupervised machine learning to identify anomalies in a marine engine’s operational data. The goal is to help shipping companies prevent engine failure, reduce downtime, and improve operational safety through early detection of mechanical issues.

## Project Overview

The dataset includes six key sensor readings (e.g. rpm, oil pressure, coolant temperature) monitored continuously across a fleet. By detecting outliers and irregular behaviour, this project supports preventative maintenance strategies.

## Business Context

Engine failure during shipping can lead to delays, safety risks, and increased operational costs. An early warning system using anomaly detection supports:
- Proactive maintenance scheduling
- Risk mitigation and crew safety
- Improved customer satisfaction through fewer delays
- Increased fleet reliability and reduced cost of breakdowns

## Objectives

- Clean and scale engine sensor data
- Apply anomaly detection methods (e.g. Isolation Forest, z-score analysis)
- Evaluate univariate and multivariate anomalies
- Recommend features and thresholds to monitor in production

## Tools and Libraries

- Python, pandas, NumPy, matplotlib, seaborn
- scikit-learn, IsolationForest
- StandardScaler, One-Class SVM

## Results Summary

- Identified high-risk ranges for features like oil temperature and rpm
- Isolation Forest detected ~3% anomalies, consistent with real-world expectations
- Generated heatmaps and distributions to assist threshold definition
- Recommended monitoring features with the strongest predictive value for early intervention

## Limitations

- Results depend on sensor accuracy and coverage across fleets
- Assumes historical data is representative of normal engine behaviour

## Next Steps

- Incorporate domain expert review of flagged anomalies
- Test real-time implementation on incoming data streams
- Develop dashboard to visualise engine risk scores

## Supporting Material

For a non-technical summary of the business application and findings, see the [Stakeholder Report (PDF)](./stakeholder_report.pdf).

---

## Contact

Created by [Matt Cocker]  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/matt-cocker-b77b49216/) or view other projects at [github.com/matt-cocker](https://github.com/matt-cocker)
