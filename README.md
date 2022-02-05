
# A Descriptive Analysis of Climate Change Accountability
### *By Sophie Yeh, Ben Bluhm, Yeonsoo Kim*

**GitHub repository: Project2_Bluhm_Kim_Yeh**

**Data Sci W200 Section Th 630**

12 December, 2021

# Analysis to answer the following
**How does severe weather experience compare between high- and low- polluters in the world?**
 - Are there more severe weather events over time? 
 - Are rich countries polluting more than poorer countries? 
 - Should rich nations compensate poorer nations for severe climate change? 


### Assumptions
- All answers to our research question is from an observational statistics perspective.
- Pollution is measured by CO2 and GHG emissions.
- Wealth of a country is measured by its GDP per capita. While this relationship is not a perfect indicator of a country’s wealth it does measure how much economic activity has occurred during a timespan and is commonly used as a metric for a healthy economy.  
- Severe weather is a subset of natural disasters. E.g. Floods, storms, droughts.  
- Collection of data is consistent over the years in the datasets.  Any variation is not due to enhancements in tracking mechanisms and/or policies.  
- Each country has unique variations in land mass, GDP, population, industries, and other metrics that may result in bias toward pollution, prosperity, or increased likelihood of disasters.  There will not be a need to do robust normalization based on the context of countries because analysis will be executed on the full set of all countries.   


### Getting started with the Notebooks
_Note: Interactive Plotly charts will not preview in Github! Run local or in nbviewer!_
- Run the data prep notebooks to produce the cleansed datasets
  `Code/mids-w200/Project2_Bluhm_Kim_Yeh/Code/1_CO2_Cleansing_Validation.ipynb`
  `Code/2_Disaster_Cleansing_Validation.ipynb`
  `Code/3_CO2_Disaster_Merge.ipynb`
- Check out the analysis and observations in 
   `Code/Analysis.ipynb`