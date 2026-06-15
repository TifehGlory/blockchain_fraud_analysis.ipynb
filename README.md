# blockchain_fraud_analysis.ipynb
End-to-end blockchain fraud investigation using graph analytics, NetworkX, Python, and the Elliptic Bitcoin Dataset. Includes risk scoring, suspicious pattern detection, compliance reporting, and an interactive dashboard.

## Project Overview
This project models 203,769 Bitcoin transactions as a directed graph to identify 
suspicious activity patterns consistent with money laundering — specifically layering 
and fan-out behaviour. A composite risk score ranks every node by structural 
importance within the network.

## Key Findings
- 159 suspicious nodes flagged across two fraud patterns
- Node 38688623: 98 incoming sources — extreme consolidation behaviour
- Node 1891081: 95 outgoing destinations — extreme dispersal behaviour
- 92 unlabelled nodes flagged — unreviewed does not mean low risk


## Tools & Libraries
Python · Pandas · NetworkX · Matplotlib · Plotly · Scikit-learn · Jupyter Notebook

## Project Files
| File | Description |
|---|---|
| `elliptic_analysis.ipynb` | Full analysis notebook |
| `elliptic_cleaned.csv` | Cleaned and merged dataset |
| `network_visualization.png` | Network graph visualisation |
| `layering_patterns.csv` | Layering fraud pattern results |
| `fanout_patterns.csv` | Fan-out fraud pattern results |
| `compliance_report.docx` | Business report for Head of Compliance |
| `fraud_dashboard.html` | Interactive Plotly dashboard |


