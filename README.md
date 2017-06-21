This data is about 911 calls in Montgomery County, PA starting from January, 2016 until May, 2017. Dataset contains following info:
1) Geographical data on incident (lat, long)
2) Short description
3) Postal code
4) Title
5) Time of the call
6) Township
7) Actual adress

Data can be downloaded at: https://www.kaggle.com/mchirico/montcoalert

First, I will load the data and have initial look at it. After splitting Title column to General and Sub titles , I will investigate the top 5 resons of each General title of calls.
Next, I will look at some Traffic Accident subtitles and see how they evolved on monthly basis
Last, I will plot Fire Accidents where one or more persons were reported as Burned. I will use OpenStreetMap for this purpose.


Libraries to be used:
Pandas
Numpy
Matplotlib
Seaborn
Folium
