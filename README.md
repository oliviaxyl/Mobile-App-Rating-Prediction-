# Mobile-App-Rating-Prediction-

![Mobileapp](https://user-images.githubusercontent.com/49653689/94883645-2ed09280-0439-11eb-9dbb-0684456da3ed.png)

#### -- Project Status: [Completed]

## Project Objective

The purpose of this project is 

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
  <img  src="![rating](https://user-images.githubusercontent.com/49653689/95032083-37b6a380-0687-11eb-94c1-e72d3cb7b6c3.png)">
</p>

###

