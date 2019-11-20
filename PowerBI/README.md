# Power BI Data Connector for Azure Time Series Insights

## This is the temporary fix and only works for Power BI Desktop. Please delete this file after December update of Power BI.

## Steps to use this connector in Power BI Desktop-
*	Create folder in your Windows system - C:\Users\<username>\Documents\Power BI Desktop\Custom Connectors\ 
*	Copy the TimeSeriesInsightsConnector.pqz file to the above folder. 
* Restart Power BI Desktop.
*	Power BI Desktop - Go to File -> Options & Settings -> Options -> Security -> Data Extensions and then choose 'Allow any extension to load without validation or warning.' 
*	Clear permissions for "Login into Azure Time Series Insights Preview"(if present). Go to Power BI Desktop - Go to File -> Options & Settings -> Data Source Settings -> Login into Azure Time Series Insights Preview.
