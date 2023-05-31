# ETL-on-Google-Cloud-Platform-using-Mage-AI-Big-Query-and-Looker
In this project, I built an end to end ETL pipeline that extracts, stores and analyzes the uber data set found [here](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

# Tools and Technologies
1. Google Platform
- [Compute Engine](https://cloud.google.com/compute) for Compute
- [Google Big query](https://cloud.google.com/bigquery)for data Storage
- [Looker](https://www.looker.com/) for Visualization

2. Mage.Ai for Orchestration

# The Process
- Data Modeling
![Data Model](Images/uber_model.png)

![Pipeline in Airflow](Images/mage.png)

![Data Visulaization in Looker](Images/looker.png)

#Appendix
- [Images](./Images) - Project Images
- [Mage Files](Mage_Files) - Mage configuration files
- Uber.ipynb
- [Serversetup.sh](./serversetup.sh) - Script to update and set up mage in Virtal Machine
- [Data](./uber_data.csv) - The data