# EQ Works-Work Sample Problems - Data Role

## Problems:

### 1- Cleanup:
Find the sample dataset of request logs in data/DataSample.csv. We consider records that have identical geoinfo and timest as suspicious. Please clean up the sample dataset by filtering out those questionable request records.

### 2. Label:
Assign each request (from data/DataSample.csv) to the closest (i.e., minimum distance) POI (from data/POIList.csv). Note: a POI is a geographical Point of Interest.

### 3. Analysis:
For each POI, calculate the average and standard deviation of the distance between the POI to each of its assigned requests. At each POI, draw a circle (with the center at the POI) that includes all of its assigned requests. Calculate the radius and density (requests/area) for each POI.

### 4.  Data Science/Engineering Tracks: Model
To visualize the popularity of each POI, map them to a scale that ranges from -10 to 10. Please provide a mathematical model to implement this, taking into consideration of extreme cases and outliers. Aim to be more sensitive around the average and give as much visual differentiability as possible.