# Zomato-Data-Analysis-and-Visualization

## Project Description

Analysing Zomato Dataset and to build a Plotly Dashboard that helps to analyze and improve zomato's business 

### Skills Used:

<a href="https://pandas.pydata.org/docs/reference/index.html">
<img alt="Pandas" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/2560px-Pandas_logo.svg.png" width="165"/>
</a>
<a href="https://plotly.com/python-api-reference/">
<img alt="Plotly" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Plotly-logo.png/1200px-Plotly-logo.png" width="165"/>
</a>
<a href="https://docs.python.org/3/c-api/index.html">
<img alt="Python" src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" width="165"/>
</a>


## Problem Statement
 
Zomato is a popular restaurant discovery and food delivery service. Data
analysis on the platform's data could be used to gain insights into customer
preferences and behavior, as well as identify trends in the restaurant industry.
To perform the analysis various _methodologies_ such as _Data Exploration, Data
Cleaning, Feature Selection And Deployment_ can be used. Additionally, various
_data visualization techniques_ like bar charts, line charts, scatter plots, etc. could
be employed to help communicate the insights gained from the
analysis.

Overall, data visualization can be used to effectively communicate the
insights from Zomato data analysis to a wide range of stakeholders, including
restaurants, food industry players, and investors.

## Work Flow

- _**Uploading the required dataset from**_
   - https://raw.githubusercontent.com/JaniceLibbyThomas/Sample_Dataset/main/Zomato.csv
   - https://raw.githubusercontent.com/JaniceLibbyThomas/Sample_Dataset/main/Country-Code.csv
   
- _**Data Cleaning:**_
  - Since taken dataset is a cleaned dataset, no cleaning operation is done.

- _**Data Engineering:**_
  - Adding new column Exchange rate of other currency to INR (Indian Rupee)
  - Adding another new column Indian Rupee by multipling cost amount which already exist in the dataframe with newly added column exchange rate.
  
- _**Data Visualization:**_
  - Visualized using Plotly Dash
