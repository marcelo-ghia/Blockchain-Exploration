Bitcoin Transaction Analysis
This repository contains Python code to analyze Bitcoin transactions using Jupyter Notebooks. The analysis focuses on the Bitcoin transaction data obtained from the public Bigquery dataset. It provides insights into the average number of transactions per year, transaction flow, fees, and explores the activity of a specific Bitcoin account.

Prerequisites
To run the analysis, you need the following:

Python (>=3.6)
Jupyter Notebook
pandas library
plotly.express library
d3fdgraph library (optional, for visualizing network graphs)

Data
The data used for analysis is obtained from the public Bigquery dataset. The dataset contains Bitcoin transaction information, including timestamps, sender addresses, receiver addresses, transaction types, and fees.

Analysis Highlights
Bitcoin Average Transactions by Year: Analyzes the average number of transactions per year from 2017 to 2023 and visualizes it using a bar chart.

Transaction History Analysis: Analyzes the transaction history of a specific Bitcoin account (bc1qxvay4an52gcghxq5lavact7r6qe9l4laedsazz8fj2ee2cy47tlqff4aj4). The analysis includes insights such as daily transaction volume, transaction types (send, receive, within the same account), and average transaction values for each type.

Transaction Flow Analysis: Identifies the accounts to which the chosen Bitcoin account (bc1qxvay4an52gcghxq5lavact7r6qe9l4laedsazz8fj2ee2cy47tlqff4aj4) has sent cryptocurrencies. Due to data limitations, the depth of the transaction flow analysis is restricted to Tier 1 transactions.

Fees Analysis: Analyzes transaction fees by transaction type (send, receive, within the same account) and provides insights into average and total transaction fees.

Note
The analysis provided in the Jupyter Notebook is based on the available data from the public Bigquery dataset. The data may not cover all Bitcoin transactions due to limitations, and some insights may be subject to further exploration with complete data.
