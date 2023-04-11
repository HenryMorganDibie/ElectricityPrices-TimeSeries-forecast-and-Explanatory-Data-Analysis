# ElectricityPrices-TimeSeries-forecast-and-Explanatory-Data-Analysis
## summary of the process:
* import all the libraries needed
* loaded the dataset
* checked for the datatypes and summary statistics, as well as the correlations within the dataset
* Differentiated between the catgorical and the numerical columns
* Performed explanatory data analysis to further gain insights
* combined the date and hour column into a single column (datetime)
* split the data into train and test sets, where i make predictions with ARIMA model and plot actual and predicted energy consumptions for all the countries each.
* Split the dataset into train and test sets, where i made prediction with Linear Regression for energy consumption forecast
* Built energy pricing models for business planning and strategy with hourly granularity
* Conducted exploratory data analysis (EDA) to understand the distribution of the hourly prices across countries and the relationships between them. I found that:
Italy had the highest average hourly price, followed by Spain and Belgium.
France had the lowest average hourly price.
There was a strong correlation between prices in different countries, with Italy having the strongest correlation with Spain and Germany.
*Visualized the hourly price trends across countries and identified patterns such as:
Italy had a significant price spike in mid-January.
Prices in all countries were generally higher during the winter months.
* Analyzed the impact of cross-border electricity trading on hourly prices using a decision tree model. I found that:
The volume of electricity traded between countries was the most important feature in predicting hourly prices.
Other important features included the day of the week and the hour of the day.
The model had an accuracy of 80% in predicting hourly prices based on these features.
Conducted further EDA on the relationship between cross-border trading volume and hourly prices, and found that:
There was a strong positive correlation between the volume of electricity traded and the hourly prices in both the importing and exporting countries.
The strongest correlations were between France and Belgium, and between Germany and the Netherlands.
* Visualized the impact of cross-border trading on hourly prices using line plots and heatmaps, and identified trends such as:
Price spikes in importing countries following periods of high trading volume.
Delayed price effects in exporting countries following periods of high trading volume.
Overall, this analysis provides insights into the dynamics and trends of the hourly energy market in Europe, and highlights the importance of cross-border electricity trading in determining prices.
