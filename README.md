# Repository for Brooke Bao's data science capstone project at Wellesley College, 2025 (affiliated with the class DS350H).

All data science capstones were required to use datasets that are made publicly available by Bluebikes. My projects explores whether bluebikes tend to accumulate at certain stations and what attributes about certain stations may predict that.

## File Structure

File/Directory | Description
------------- | -------------
data/raw_bluebike | Original datasets from the bluebikes website
data/bluebikeSummers.csv | Cleaned dataset for bluebike trips
data/stationdata.csv | Cleaned dataset with bike flows for stations
1_bluebiketrips_datacleaning.R | R script used to clean bluebike trip data
2_cluster_python.iypnb | Python used to merge trip data with station data and cluster the station data
3_predictions.R | R used to see it station attributes can predict which group station is clustered into
finalprojectposter | Final Project Poster
other | HTML of the map created to visualize clusters on map
