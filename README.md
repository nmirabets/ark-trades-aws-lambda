# ARK Trades - AWS Lambda Function
### Project Overview

---

In this project, the objetive is to develop a python script that:

1. Downloads daily trade data from [ARK Invest's (an ETF fund) website](https://ark-funds.com/download-fund-materials/) in CSV format
2. Cleans and formats the data
3. Inserts the data into a AWS RDS MySQL database

The deployment is done using a combination of AWS services as seen below.

![Flow chart](./resources/flow_chart.png)

The trade data is currently available via SQL query. 

### Future developments

---

- [ ]  Add FastAPI to offer data as through an open API
- [ ]  Add podcast transcriptions to database
- [ ]  Add research paper summaries
