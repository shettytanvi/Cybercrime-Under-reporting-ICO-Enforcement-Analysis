# Cybercrime-Under-reporting-ICO-Enforcement-Analysis
## Business Requirements
This Power BI-driven analysis investigates cybercrime under-reporting in the UK and evaluates whether cybersecurity incidents lead to enforcement by the Information Commissioner’s Office (ICO). The study aids regulatory bodies and organisations in understanding patterns, improving reporting mechanisms, and enhancing cyber resilience.

• Understand discrepancies between Action Fraud (AF) and ICO cybercrime data.
• Identify under-reported cyber threats like malware and unauthorised access.
• Provide insights into the effectiveness of ICO enforcement.
• Predict trends in cybercrime using regression-based forecasting.
• Recommend data harmonisation and collaboration for robust incident response.

## KPI’s
• Cybercrime Volume Analysis
Compare and evaluate cybercrime incident counts across Action Fraud and ICO reports.

• Reporting Discrepancy Metrics
Quantify the difference in incident types and volume reported between AF and ICO.

• Enforcement Correlation Insight
Assess potential links between reported breaches and ICO enforcement actions.

• Predictive Modelling Accuracy
Evaluate regression model performance in forecasting future incidents.

• Under-reporting Indicators
Track signs of probable under-reporting based on anomaly patterns and test results.

## Problem Statement
Cybercrime incidents are significantly under-reported in the UK. There is limited visibility into whether these incidents lead to enforcement by regulatory bodies such as the ICO. Discrepancies in reported data further obscure organisational readiness and public awareness. This dashboard aims to address these gaps and propose strategic recommendations.

## Chart Requirements
• Cybercrime trend by year (Line Chart):
Track annual reporting trends from Action Fraud and ICO.

• Cybercrime incidents by type (Bar Chart):
Visualise distribution of malware, extortion, ransomware, and unauthorised access.

• Report source comparison (Stacked Bar/Area Chart):
Compare AF vs ICO reports for key incident categories.

• Predictive trend (Line Forecast Chart):
Show projected cybercrime incidents for 2023 and 2024 based on regression analysis.

• Under-reporting analysis (Box Plot):
Identify anomalies in reporting frequency by organisation and incident type.

• Geographical analysis (If applicable, Filled Map):
Map regional variations in reported cyber incidents (optional if data allows).

## Findings
• Discrepancy in Reporting Volumes

Malware incidents reported by Action Fraud (AF) are substantially higher than those reported by the ICO.

Statistical tests (Welch t-test) indicate that this difference is significant for malware but not significant for unauthorised access incidents.

• Inconsistency Across Organisations

The variation in reported incidents between AF and ICO suggests different definitions, awareness levels, or accessibility of reporting systems.

ICO shows more reports of unauthorised access, possibly reflecting their role in handling data protection breaches under GDPR.

• Lack of Correlation Evidence for Enforcement

There is no direct evidence that ICO enforcement actions are significantly correlated with the number of cybersecurity breaches reported.

Data limitations (e.g., lack of enforcement/prosecution figures) prevent a definitive conclusion.

• Predictive Modelling Limitations

Regression models forecasted increases in cyber incidents (e.g., Action Fraud predicted ~9,974 incidents in 2023), but:

The R² values were low (Action Fraud: 17%, ICO: 29%), indicating weak predictive power.

P-values were above 0.05, suggesting predictions might reflect random noise rather than real trends.

• Evidence of Under-reporting

Findings support that cybercrime is under-reported, particularly by businesses.

Barriers to reporting include lack of awareness, fear of reputational damage, or unclear processes.

• Need for Data Harmonisation

Disparate data formats and terminology between AF and ICO hinder consistent analysis.

Standardisation and integration of datasets is recommended to improve national cybercrime insights.

• Public Awareness and Education

Variance in reporting suggests gaps in public knowledge of where and how to report cyber incidents.

Joint outreach efforts by AF and ICO could enhance reporting accuracy and volume.

• Call for Advanced Modelling Techniques

Traditional linear regression is insufficient; future work should apply AI/ML techniques for better accuracy in cyber threat prediction.
