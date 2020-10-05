# Mobile-App-Rating-Prediction-

<p align="center">
  <img weight=500 height=300 src="https://user-images.githubusercontent.com/49653689/94883645-2ed09280-0439-11eb-9dbb-0684456da3ed.png">
</p>

#### -- Project Status: [Completed]

## Project Objective

The purpose of this project is to develop models to predict user rating based on various app features and app descriptions. 

### Methods Used

* Exploratory Data Analysis
* Random Forest Regression 
* K Nearest Neighbors
* Text Mining
 
### Technologies

* Jupyter, Python 3, RStudio
* Pandas, NumPy, sklearn, PyTorch, SciPy, Matplotlib

## Project Description

### Data 

The data was extracted from the iTunes Search API at Apple Inc website. The original data set has
16 input variables, and total of 7197 observations before data pre-processing. The data set is as
follows:

<p align="center">
  <img  src="https://user-images.githubusercontent.com/49653689/95031718-6af83300-0685-11eb-93ba-5b009f51c5e7.png">
</p>

### Resampling

The rating score of the app data ranges from 0 to 5, but the number of ratings counts on each rating score has extremely differences. Most of rating scores distribute around 4 and 4.5. Rating score of 1 and 1.5 has the lowest percentage among the whole rating score range shown in figure. However, to predict the popularity of mobile app. Both the high-rating data and low-rating data are essential to extract the feature importance and build predictive models. Therefore, oversampling method was applied to balance the number of rating counts of different rating scores. For this project, all the rating counts were over sampled to be the same as that of 4.5.
<p align="center">
  <img  src="https://user-images.githubusercontent.com/49653689/95032109-53ba4500-0687-11eb-9b73-95ea3945a554.png">
</p>

### Model Training & Hyperparameter Tuning

* Random Forest (max_features, n_estimators)
* K Nearest Neighbors (n_neighbors, leaf_size, Weights, algorithm)


### Text mining

* Use word2vec to explore text similarity
* RNN (LSTM & GRU)

<p align="center">
  <img  weight=600 height=400 src="https://user-images.githubusercontent.com/49653689/95033818-7fd8c480-068d-11eb-83c6-a7867d1ae577.png">
</p>

* LightGBM

### RSE 

* Random Forest: 0.268
* KNN: 0.731
* RNN: 0.755
* LightGBM: 0.314


