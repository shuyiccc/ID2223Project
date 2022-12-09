# ID2223Project

Group 23: Ernan Wang, Shuyi Chen.

#Proposal
In this project, we are planning to build a scalable prediction service system based on machine learning that can predict weather conditions in Beijing, China.

### Data source
The real-world data source we select is [Visual Crossing](https://www.visualcrossing.com/) where easy access to worldwide weather data is offered. We would like to work on [Beijing](https://www.visualcrossing.com/weather/weather-data-services/Beijing?v=api). It covers a lot of information related to the weather and updates daily.

### Prediction problem that will be solved
Using weather data including temperature, wind, precipitation etc. to predict the weather condition such as sunny, cloudy, rainy, snowy etc. in Beijing.

### Data model with features and labels
As we mentioned above, features include temperature, wind, precipitation etc. and labels include sunny, cloudy, rainy, snowy and so on.

### Build a feature pipeline
We plan to clean data, extract features from the collected data, process labels, and then upload the features and labels to the feature store in Hopsworks.

### Build a training pipeline
We propose to use XGBoost model to train and then fine-tune the model in order to get higher accuracy in predicting the weather condition.

### User Interface
There will be two UI in the Hugging Face. One is interactive and the user can test the model, and the other is to display the performance of recent weather predictions.

