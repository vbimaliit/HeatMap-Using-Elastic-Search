# HeatMap
Fetching the data from Elastic search and plotting HeatMap
Data is first read in .csv format into Panda data.
Convert the data from Panda to JSON format.
Used the Bulk API of elastic search to create index on all the data.(To make the insertion much faster)
Used scorll API of elastic to process the full data as it is not possible to fetch all the data at sigle point of time.
Used the latitude and Longitude field from the data and plot the HeatMap using Folium.
