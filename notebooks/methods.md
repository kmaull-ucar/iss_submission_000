### METHODS
[auto-generated]

#### Data Collection
We collected data from three APIs: AirNow {cite}`noauthor_airnowgov_nodate`, OpenAQ {cite}`openaq_openaq_nodate` and World AQ Index {cite}`project_worlds_nodate`. We accessed the following endpoints from each API: `/endpoint1` for AirNow, `/r/a/w/endpoint2` for OpenAQ, and `/t/h/a/t/endpoint3` for WorldAQ. The data retrieved included lat/lon coordinates for all stations globally.

#### Data Processing
The data was cleaned by removing unnecessary information and dealing with missing values. The data was then normalized by standardizing formats across different APIs. Finally, the data was transformed by aggregating the data from each endpoint.

#### Data Analysis
We used descriptive statistics to summarize the data and inferential statistics to test hypotheses. We also built a predictive model using a machine learning algorithm. All assumptions made during the analysis were checked using appropriate statistical tests.

#### Tools Used
We used Python as our primary programming language and the pandas library for data manipulation. We also used the requests library to interact with the APIs and the scikit-learn library for machine learning.
