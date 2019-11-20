# Power BI Data Connector for Azure Time Series Insights

## If you are facing the following error after sign in, use this temporary fix which fixes the 404 error. This only works for Power BI Desktop. Please delete this file after December update of Power BI.

![Alt text](404Error.jpg?raw=true "Title")

## Steps to use this connector in Power BI Desktop-
*	Create folder in your Windows system - C:\Users\\\<username>\Documents\Power BI Desktop\Custom Connectors\ 
*	Copy the TimeSeriesInsightsConnector.pqx file to the above folder. 
* Restart Power BI Desktop. 
*	Clear permissions for "Login into Azure Time Series Insights Preview"(if present). Go to Power BI Desktop - Go to File -> Options & Settings -> Data Source Settings -> Login into Azure Time Series Insights Preview.
