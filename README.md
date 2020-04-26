# Predicting-Bike-Sharing-Patterns
<h2>Project Overview</h2>

Building and Training a Artificial Neural Network(ANN) From Scratch To Predict The Number Of BikeShare Users On a Given Day.Predicting the number of bikeshare riders on a given day is very useful for a bikesharing company Because they want know how many bikes they really need,which can help solve two Potential Problems for the Comapany:<br>





<li><b>If The Company Has Too Few Bikes,Then The Company Will Be Loosing Money From The Potential Riders.</b></li>

<li><b>If The Company Has Too Many Bikes, Then They Wil Be Wasting Money On Bikes That Are Simply sitting Around.</b></li>
<br>



 Hence the Company has to Know how many bikes it needs in the near future,One of the best ways to predict is by looking at the Historical Data of the Company, A Neural Network model is built from the ground up before going to the higher level implementations of Tensorflow,Pytorch or other Deep Learning frameworks,it also helps to gain the higher level Understanding of forward propogation,gradient descent,backpropagation etc.
 
 <h2> Dataset </h2>
 
 The Data comes from the UCI Machine Learning Database:https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset
 
 
 [Download the Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
 
This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.

<h2>Dataset Information</h2>

Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.

Apart from interesting real world applications of bike sharing systems, the characteristics of data being generated by these systems make them attractive for the research. Opposed to other transport services such as bus or subway, the duration of travel, departure and arrival position is explicitly recorded in these systems. This feature turns bike sharing system into a virtual sensor network that can be used for sensing mobility in the city. Hence, it is expected that most of important events in the city could be detected via monitoring these data.

<h2>Dataset Attribute Information</h2>

Both hour.csv and day.csv have the following fields, except hr which is not available in day.csv

- instant: record index
- dteday : date
- season : season (1:winter, 2:spring, 3:summer, 4:fall)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : weather day is holiday or not (extracted from [Web Link])
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
+ weathersit :
- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered
 
<h2>Softwares and Libraries</h2>

[Python 2.7 or Higher](https://www.python.org/downloads/)

[Numpy](https://pypi.org/project/numpy/)

[Matplotlib](https://pypi.org/project/matplotlib/)

[Pandas](https://pypi.org/project/pandas/)

[Jupyter Notebook](https://jupyter.org/install)

<h2>Project Instructions</h2>

Download the project materials from the GitHub repository by using the Download  option or Clone the github repository.After Dowloading or Cloning Navigate to the Home Folder of the Project.

```
git clone https://github.com/ash-code007/Predicting-Bike-Sharing-Patterns.git
cd Predicting-Bike-Sharing-Patterns
```
Run the following to open up the notebook server:jupyter notebook

In your browser, open Bike_Sharing_Neural_Network.ipynb

Edit the Neural_Network.py python file, whose components are imported into the notebook at various places.

<h2>Results</h2>

<h2>Correlation Between Different Attributes In The Dataset</h2>

![Correlation](https://github.com/ash-code007/Predicting-Bike-Sharing-Patterns/blob/tree/master/Bike_Sharing_Dataset/Corr.png)

<h2>Training and Validation Loss</h2>

![Training and Validation Loss](https://github.com/ash-code007/Predicting-Bike-Sharing-Patterns/blob/master/Bike_Sharing_Dataset/Train_val.png)

<h2>Predictions On the Test Dataset</h2>

![Predictions](https://github.com/ash-code007/Predicting-Bike-Sharing-Patterns/blob/tree/master/Bike_Sharing_Dataset/Pred.png)



