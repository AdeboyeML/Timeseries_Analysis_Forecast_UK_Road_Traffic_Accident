[//]: # (Image References)

[image1]: ./uk_region.png "uk_road"
[image2]: ./analytics_viz/veh_trend.png "veh_trd"
[image3]: ./analytics_viz/pedal_trd.png "pedal_trd"
[image4]: ./analytics_viz/van_trd.png "van_trd"
[image5]: ./analytics_viz/rd_cat.png "rd_cat"
[image6]: ./analytics_viz/reg_trd.png "regions"
[image7]: ./analytics_viz/veh_flow.png "veh_flow"

# Predictive_Analytics_UK_Road_Traffic_Accident


#### This project entails performing in-depth descriptive analysis and data visualization on the United Kingdom road traffic (2000 - 2018) and accident dataset (2005 - 2014) and further forecasting / predicting the rate of accident for the next two years based on the available time series dataset.

#### It is recommended to view the notebook in using [nbviewer](https://nbviewer.jupyter.org/) as most of the plots and figures are interactive, the nbviewer links for each category (notebook) is provided below.

This project is broken down into 3 categories:

#### 1. Road Traffic Analytics and Visualization [uk_road_traffic](https://nbviewer.jupyter.org/github/AdeboyeML/Predictive_Analytics_UK_Road_Traffic_Accident/blob/master/UK_Traffic_Analysis_Visualization.ipynb)


- This aspect of the project gives takes a descriptive look into United Kingdom (UK) long-term road traffic trends between 2000 - 2018 based on estimated **Annual average daily flows (AADFs) and volume of traffic (i.e. miles driven per year for each vehicle on a particular road)** for vehicle types, road networks, geographical regions, road types and highway authorities.


#### 2. Road Accident Analytics and Visualization [uk_road_accident](https://nbviewer.jupyter.org/github/AdeboyeML/Predictive_Analytics_UK_Road_Traffic_Accident/blob/master/UK_road_accident_analytics.ipynb)


- This aspect of this project takes a detailed look into United Kingdom (UK) long-term road accident trends between 2005 - 2014, which includes but not limited to potential casualties due to road accidents, areas most affected by accidents, highway authorities notorious for road accidents and those that are the "safest", conditions likely to cause accidents and road types and geographical regions well known for acidents.


#### 3. Timeseries forecasting of the rate of road accident in UK for the next 2 years. [TimeSeries Forecast](https://nbviewer.jupyter.org/github/AdeboyeML/Predictive_Analytics_UK_Road_Traffic_Accident/blob/master/UK_Road_Accident_Timeseries_Forecasting.ipynb)


- The aim of this part is to use statistical and machine learning models to forecast the number of casualties due to road accidents 2 years into the future based on the available dataset, also this project entails experimenting on the different kinds of Long-Short Term Memory (LSTM) Neural Networks (i.e. LSTM, GRU - Gated recurrent units, Bidirectional LSTM and Convolutional LSTM) and trying to see if they can learn from the small time series dataset.


    - For this project we will use the following models for forecasting:
      - SARIMA (Seasonal - Autoregressive Integrated Moving Average)
      - Facebook Prophet
      - LSTM: 
            
            - LSTM
            - GRU
            - Bidirectional LSTM
            - Convolutional LSTM

### Python Libraries Utilized

    - Pandas
    - Numpy
    - Sci-kit learn
    - Statsmodels
    - Plotly
    - GeoPandas
    - Keras
    - Facebook Prophet
    - Matplotlib

![uk_road][image1]


### Road Analytics Results and Visualization  (Just a few insightful visualizations.....)

![veh_trd][image2]
![pedal_trd][image3]
![van_trd][image4]
![rd_cat][image5]
![regions][image6]
![veh_flow][image7]
