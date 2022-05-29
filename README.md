# bellabeat-analysis
This notebook documents consumer insight analysis for **Bellabeat**, a wellness tech company, and as part of an individual capstone project to the ***Google Data Analytics Professional Certificate Course.***

Validation, processing, and analyzing the data was done with SQL using the BigQuery API and documented in a Jupyter Notebook.

Additionally, Tableau was used to create data visualizations for the notebook and a [**high-level report**](https://public.tableau.com/app/profile/phil.lin/viz/BellabeatAnalysis_16486095004470/STORY) summarizing the key insights and marketing recommendations to the executive team.

***BUSINESS TASK:** The executive team would like to understand how non-Bellabeat consumers use smart devices and then leverage these insights to find opportunities for growth. In addition, they would like recommendations for a marketing strategy based on this analysis. A public-domain dataset of Fitbit users has been provided.*

## REPORT

***PART 1** | Consumer Insight Analysis*

This section examines users' level of engagement with the Fitbit, analyzes their usage habits, and then constructs a user profile based on these findings.

***PART 2** | Marketing Recommendations*

This section outlines actionable recommendations for the marketing team based on key insights  from the data in Part 1.

## DATA

The dataset is a collection of personal tracking data submitted by Fitbit users who responded to a distributed survey via Amazon Mechanical Turk. 

33 Fitbit users consented to providing [data](https://www.kaggle.com/datasets/arashnic/fitbit) on physical activity, sleep, heart rate, and weight for the period 03.12.20166 to 05.12.2016. The users’ privacy has been protected by only referring to individuals via randomly generated ID numbers. 

The data is in the public domain (CC0 1.0 Universal Public Domain) and was first accessed via  Kaggle (uploaded by user MÖBIUS), but the data originates from Zenodo, an open access research data repository developed as part of the European OpenAIRE program and maintained by CERN (European Organization for Nuclear Research). The original dataset on Zenodo can be found [here](https://zenodo.org/record/53894#.Yn1gHhPMJqv).

## Requirements
- [Python 3.8.6](https://www.python.org/downloads/release/python-386/)
- [Jupyter Notebook](http://jupyter.org/)

## Dependencies
- [pandas](https://pandas.pydata.org/)
- [pandas_gbq](https://pandas-gbq.readthedocs.io/en/latest/)
- [google-cloud-bigquery](https://googleapis.dev/python/bigquery/latest/changelog.html)

## License
- [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
