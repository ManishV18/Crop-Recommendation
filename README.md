# Crop Recommendation
 
## Problem Statement:
To build a robust model to give correct and accurate predictions of crop sustainability in a given state for the particular soil type and climatic conditions. 

## Data fields:
N - ratio of Nitrogen content in soil <br>
P - ratio of Phosphorus content in soil <br>
K - ratio of Potassium content in soil <br>
temperature - temperature in degree Celsius <br>
humidity - relative humidity in % <br>
ph - ph value of the soil <br>
rainfall - rainfall in mm 

## Algorithm:
K-nearest neighbors (KNN) algorithm uses ‘feature similarity’ to predict the values of new
datapoints which further means that the new data point will be assigned a value based on how closely it matches the points in the training set.This algorithm is used to extract the knowledge based on the samples distance function and majority of k-nearest neighbors. It checks the whole dataset to find the k nearest instances to the new instance and then output the mode for a classification problem.

## Advantages:
-> The selection of crops & cropping system plays a major role in improving the
productivity and profitability of the farmers.
-> Provide a recommendation of the best suitable crops in the area so that the farmer does
not incur any losses.
-> Crop recommendation system thereby helps farmers during this decision making process
by considering various parameters such as temperature, rainfall, and seasons and agroecological situations
 -> Provide profit analysis of various crops based on previous years data 

## Result
We were able to develop a crop recommendation system that can determine which crop to
grow based on the attributes of the soil. We employed KNN algorithm and found it works best for soil classification which is the basis of our crop recommendation system. Our final system using the K-Nearest Neighbor(KNN) algorithm yields an accuracy of 96 % as shown in the discussion of our results.

