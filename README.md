# -churn-risk-advisor
## Model Card: Churn Risk Advisor v1.0

**Purpose:** Predict customer churn risk to help telecom companies prioritize customer retention.

**Limitations:** Not intended for credit decisions, pricing, or denying services.

**Dataset:** IBM Telco Customer Churn, containing 7,043 customers.

**Model:** Selected using 5-fold cross-validation. Uses 30 encoded features.

**Performance:** CV AUC: [your mean ± standard deviation]; Test AUC: [your test AUC].

**Decision Threshold:** 0.30 (subject to confirmation from your cost analysis).

**Limitations:** Trained on US telecom data, so results may not generalize to Pakistan. Predictions show learned associations, not guaranteed causes.

**Fairness:** Recall across gender and senior-citizen groups should be evaluated.

**Owner:** Muhammad Bilal  
**Version:** 1.0  
**Date:** October 2026
