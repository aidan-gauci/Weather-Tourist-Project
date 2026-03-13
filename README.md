# Weather Tourist Project
Malta is internationally recognised for its Mediterranean climate, diverse history and architectural heritage. Although a link between tourism and sunny weather is obvious, the last decade has seen a massive surge of tourists, most of which come during the summer months.

As a Maltese citizen, I can confirm that the weather now is different as to how it was a decade ago, but as temperatures rise, the number of tourists still increases. I wanted to investigate this change through tangible analytical methods whether the weather has as much of an influence on tourism as one may think.

**Technologies Used:**

* Python 3.X
* Jupyter Notebook
* *Libraries:* pandas, numpy, scikit-learn, matplotlib, openmeteo-requests, eurostat, requests-cache, retry-requests, seaborn

**Data Sources & Credits:**

* Open-Meteo

Zippenfenig, P. (2023). Open-Meteo.com Weather API [Computer software]. Zenodo. https://doi.org/10.5281/ZENODO.7970649

* Eurostat

European Commission, Eurostat, *Weather Tourist Project*, Publication Office of the European Union, 2026, https://ec.europa.eu/eurostat/databrowser/view/tour_occ_ninat__custom_20507746/default/table?lang=en

* Google Trends

Google. 2026. Google Trends. Retrieved 2026, from https://trends.google.com.

**Methodology:**

* Correlation Analysis: Used to quantify the link between specific weather features and tourism interest.

* Data Visualisation: Used visualisations in order to show correlations and trends in a comprehensive manner.

* Search Trend Mapping: Used Google Search data ('malta travel') as a key for finding travel intent.

* Anomaly Investigation: Analysed how external infleunces, such as the 2020–2022 COVID pandemic, impacted the typical relationship between climate and tourism.

* Historical Trends: Identified whether the surge in tourism numbers of the last decade correlate directly with the shifting weather data from 2010 to 2025.

**Conclusions:**

Tourism in Malta is heavily influenced by the weather conditions. Traveller intent (via Google Trends) is seen not just during good weather, but before it. The high temperature stability makes weather the most consistent variable for predicting annual tourism spikes.

**How to Run:**

1. git clone https://github.com/aidan-gauci/Weather-Tourist-Project
2. cd Weather-Tourist-Project
3. pip install -r requirements.txt
4. jupyter notebook

**Limitations:**

* Wind speed structural break (2016-2018)

* COVID-19 period causing skewed visualisations.

* Limited datapoints (192) due to a lack of accessible data.
