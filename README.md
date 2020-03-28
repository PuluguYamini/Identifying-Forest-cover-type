# Identifying-Forest-cover-type

# ABSTRACT
Ensemble learning approach methods find application in solving various problems ranging from a bit harder to severe complexity problems. These models in Machine Learning are known for their better predicting results for any given large data sets. Here in the project we worked on various ensemble learning approaches for solving a problem on “Identifying Forest Cover”. The dataset for the given problem comprises of some features collected on the forest cover and also explaining the fit of various models for the given problem.

# Introduction
We would like to introduce the problem in this section. In this experiment we will be analysing various machine learning algorithm on Forest Cover Type. We need to predict the cover type using the given data. We will also analyse various parameters of the applied algorithm and view the effect on the dataset. Parameter tuning using Grid search is done. The dataset is asking one to predict the type of forest cover from given cartographic variables. The actual forest cover was modelled into a 30 by 30-meter cell and was issued by USFS. The study includes four different types of wilderness areas and 7 different types namely Spruce, Lodgepole Pine, Ponderosa Pine, Cottonwood, Aspen, Douglas-fir, Krummholz. 

# Misdescriptions of dataset (Data Exploration)
The data is partially raw format where some of the variables are in binary as wilderness areas and soil type. The training set has a total of 15120 observations containing both the features and cover type whereas the test set contains only the features. It has a total of 565892 observations.

The following are the data fields:
•	Elevation - Elevation in meters
•	Aspect - Aspect in degrees azimuth
•	Slope - Slope in degrees
•	Horizontal_Distance_To_Hydrology - Horz Dist to nearest surface water features
•	Vertical_Distance_To_Hydrology - Vert Dist to nearest surface water features
•	Horizontal_Distance_To_Roadways - Horz Dist to nearest roadway
•	Hillshade_9am (0 to 255 index) - Hillshade index at 9am, summer solstice
•	Hillshade_Noon (0 to 255 index) - Hillshade index at noon, summer solstice
•	Hillshade_3pm (0 to 255 index) - Hillshade index at 3pm, summer solstice
•	Horizontal_Distance_To_Fire_Points - Horz Dist to nearest wildfire ignition points
•	Wilderness_Area (4 binary columns, 0 = absence or 1 = presence) - Wilderness area designation
•	Soil_Type (40 binary columns, 0 = absence or 1 = presence) - Soil Type designation
•	Cover_Type (7 types, integers 1 to 7) - Forest Cover Type designation

The wilderness areas are:
1-Rawah Wilderness Area
2-Neota Wilderness Area
3-Comanche Peak Wilderness Area
4- Cache la Poudre Wilderness Area

# Conclusion:
The Accuracies we got for each model are:
KNN Classifier-83.9%
Naive Bayes-60.1%
Random Forest-86.4%
Gradient Boosting-84.5%
We got the highest accuracy for random forest algorithm.


