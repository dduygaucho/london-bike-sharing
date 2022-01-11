# London Bike Sharing

This project was done as a personal project

-- Status --  Waiting for upgraded model to improve mean squared error and further analysis/ conclusion on trends

[Click here to view the Notebook](https://github.com/dduygaucho/london-bike-sharing/blob/main/London_bike_sharing.ipynb)


![alt text](https://github.com/dduygaucho/london-bike-sharing/blob/main/cycling.jpg?raw=true)

# Source <br/>

Kaggle: <a href = "https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset"> Click this link to view the full dataset and competition <a/>
  
# Stage <br/>
  
## Stage 1: Data cleaning with Pandas
  Our goal is to predict the number of future bike shares given the historical data of London bike shares

## Stage 2: Data exploration with Pandas and seaborn

After conducting feature engineering, some major trends are noted:
    <li> There is a seasonal trend in the dataset: Summer months are good for business because the weather is dry, which facilitates cycling. </li>
    <li> The golden business hour is at 8 A.M and 6 P.M, which is the working time</li>
    <li> More people use the service in weekdays than at the weekends</li>

## Stage 3: Data modelling using Bidirectional LSTM

Train the model with a timestep of 10 hours, which yields a mse of 0.035 on the test set
  <br/>
![alt text](https://github.com/dduygaucho/london-bike-sharing/blob/main/Prediction.jpg?raw=true)

 
  

