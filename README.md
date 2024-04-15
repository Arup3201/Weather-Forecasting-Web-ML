# Web-Based Weather Forecasting App

This project entails developing a Django-based web application for weather forecasting. Users input their location to view a 5-day weather forecast with intuitive visualization. By leveraging machine learning algorithms trained on historical weather data, the application provides accurate predictions. The benefits include empowering users with accessible and reliable weather information for planning activities. Through seamless integration of Django backend and frontend technologies, the project aims to deliver a user-friendly and informative weather forecasting experience.

Dataset Description: [Dataset Link](https://corgis-edu.github.io/corgis/csv/weather/)

I took some reference from these papers-
- [Convolutional LSTM Network: A Machine Learning Approach for Precipitation Nowcasting](https://arxiv.org/pdf/1506.04214v2.pdf)
- [Deep Uncertainty Quantification: A Machine Learning Approach for Weather Forecasting](https://arxiv.org/pdf/1812.09467v3.pdf)
- [Deep multi-stations weather forecasting: explainable recurrent convolutional neural networks](https://arxiv.org/pdf/2009.11239v6.pdf)
- [Smart Weather Forecasting Using Machine Learning: A Case Study in Tennessee](https://arxiv.org/pdf/2008.10789.pdf)

I am planning to use the OpenWeatherMap API to get the current weather conditions and show it on the front-end. Also, I am getting the previous N-Days weather condition data to put in the model and get the 5-days forecasting.
API call to get current weather conditions: [Link to API call](https://openweathermap.org/api/one-call-3#current)
API call to get previous wather conditions: [Link to API call](https://openweathermap.org/api/one-call-3#history)
