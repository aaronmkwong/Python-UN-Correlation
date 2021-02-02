# Python-UN-Correlation

**Purpose**

The objective of the program is to determine the extent to which gross domestic product per capita explains the variability in suicides per capita on a country, region and oecd membership basis. Also, the countries and contiguous time period duration to be included in the analysis is automatically determined, i.e. a period greater than or equal to 10 years, which includes the United States and Canada and with the minimum amount of countries that have any missing years. Correlation is measured as r2 using the numpy corrcoef function. The visualization is interactive insofar as the user can change the countries displayed by region for the "countries" r2 scatter plot and trend lines. The program results are intended to be a robust initial exploration of the "what" to highlight concerning trends or unexpected relationships which would be investigated in more detail in some future extension of this program.   

**Visualization of Results**

Europe is selected for the example.

![alt text](https://github.com/aaronmkwong/Python-UN-Correlation/blob/main/Python_UN_Correlation.JPG)

**Data Sources**

Compiled and available on Kaggle by Russell Yates. https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016.

United Nations Development Program. (2018). Human development index (HDI). Retrieved from http://hdr.undp.org/en/indicators/137506.
World Bank. (2018). World development indicators: GDP (current US$) by country: 1985 to 2016. Retrieved from http://databank.worldbank.org/data/source/world-development-indicators#. [Szamil]. (2017). Suicide in the Twenty-First Century [dataset]. Retrieved from https://www.kaggle.com/szamil/suicide-in-the-twenty-first-century/notebook.
World Health Organization. (2018). Suicide prevention. Retrieved from http://www.who.int/mental_health/suicide-prevention/en/.

Country Classification. https://datahelpdesk.worldbank.org/knowledgebase/articles/906519.
OECD Member. https://data.worldbank.org/region/oecd-members?view=chart.
