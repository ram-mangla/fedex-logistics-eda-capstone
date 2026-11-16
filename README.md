# FedEx Logistics Performance Analysis (EDA Capstone)

Exploratory data analysis of the SCMS delivery history (10,324 shipments, 43 countries, 2006-2015): where and why do shipments miss the scheduled delivery date?

- `FedEx_Logistics_EDA_Capstone.ipynb` - full analysis (runs top to bottom in Google Colab; dataset is downloaded automatically)
- Key findings: 11.5% of shipments are delayed; the RDC route is the strongest driver (odds ratio 4.8); truck is best on direct drops but worst from the RDC; FCA/CIP terms are almost never late; lead time does not protect against delay; insurance follows line value, not weight.
- Limitation: 61% of shipments show delay exactly 0, so date recording may shape the results.
