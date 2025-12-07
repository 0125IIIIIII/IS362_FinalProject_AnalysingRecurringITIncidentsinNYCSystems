Identifying recurring IT incidents using root cause and SLA metrics in NYC government systems

Overview
This project combines two data sources:
- NYC Open Data 311 Service Requests (structured relational data).
- NYC Office of Technology & Innovation (OTI) dashboard (unstructured HTML text).

Requirements:
- Python 3.11+
- Libraries: pandas, numpy, requests, beautifulsoup4, seaborn, matplotlib, scipy, re

Goals:
- Detect recurring incident categories.
- Quantify SLA breach likelihood.
- Tag systemic root causes.
- Visualize incident trends and SLA risks.

Workflow:
1. Acquire 311 data via API.
2. Scrape OTI dashboard for incident updates.
3. Clean and normalize both datasets.
4. Merge by category and date proximity.
5. Compute SLA compliance and root cause tags.
6. Visualize trends and perform chi-square analysis.

