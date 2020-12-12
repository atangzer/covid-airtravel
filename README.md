# CMPT 353 Final Project

Topic: Investigating Airport Data in North American Airports in the year preceding (and during) the COVID-19 pandemic.

Contributors: Anna Tang, Clement Ip, Erica Ho

## Instructions:
It is recommended that Python 3.7+, and the Jupyter Notebook be installed. These can be easily installed with the follwing commands (for Debain/Ubuntu):
```
sudo apt-get install python3 python3-dev python3-pip
sudo apt-get build-dep python3-scipy python3-matplotlib
```
Windows and/or Mac users can opt to use the Anaconda package found [here](https://www.anaconda.com/products/individual).

Additionally, the following libraries are required for this project and can easily be installed with pip:
```
pip install scipy pandas numpy matplotlib seaborn sklearn scipy geopandas contextily descartes shapely
```

Work for each airport can be viewed by running its respective .ipynb notebook file.

## Output

In this project we develop machine learning models that extrapolate and predict how airport traffic will fare in YVR, YEG, YYZ, and YUL during the pandemic. We also analyze the correlation between airport traffic and the number new cases per day, as well as the cumulative number of confirmed cases. 

Results of our analyze can be viewed by running each of the available .ipynb notebook files.

## File Directory 

```
353project
├── Airport-Data -> Contains the airport traffic data for each airport.
├── Archived-Data -> Contains the scripts used to filter and produce dataframes for analysis.
├── Covid-Data -> Contains the COVID-19 data for each province.
├── graphs -> Graphs generated by the notebooks are saved here.
├── analyze_covid_hubs.ipynb -> An intial examination of the province's Covid situation.
├── analyze_airport_hubs.ipynb -> An intial examination of the airport's traffic trend.
├── analyzeYEG.ipynb -> Data and results for Calgary (YEG)
├── analyzeYUL.ipynb -> Data and result for Monteral (YUL)
├── analyzeYVR.ipynb -> Data and results for Vancouver (YVR)
├── analyzeYYZ.ipynb -> Data and results for Toronto (YYZ)
```
