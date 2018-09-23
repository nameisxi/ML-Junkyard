# ML-Junkyard
![picture alt](https://imgs.xkcd.com/comics/machine_learning.png)

# Contents
* Kaggle
    * [House Price Prediction Exercise](https://github.com/nameisxi/ML-Junkyard/#kaggle)
* FastAI
    * [Lesson 1](https://github.com/nameisxi/ML-Junkyard/#fastai)
    
# Kaggle 
### House Price Prediction Exercise
[This was my first machine learning exercise, and well, it probably seems like it. The exercise was pretty structured, but I tried to make mine a bit different and experiment on the go, as often as possible. My solution only uses a simple decision tree to make the house price predictions, but I think that it turned out to be just fine, even though there is some room for improvement.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Housing-Prices-Prediction-Exercise/Kaggle-House-Price-Prediction-Exercise.ipynb)

### House Price Prediction Competition
[This was my first Kaggle competition submission, and it's basically only an improved version of my earlier house price prediction exercise. This time instead of decision trees I decided to use random forest regressor, and it turned out to lower the error from 18K USD to roughly 10K USD.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Housing-Prices-Prediction-Competition/Kaggle-House-Price-Prediction-Competition-Solution.ipynb)

### Digit Recognizer Competition
[This is my first picture classification competition and I decided to use KNN mainly because I wanted to understand the algorithm well. CNN's definitely perform better, but I felt the need to understand KNN first. Final accuracy score with this pure Python implementation is 97.07%.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Digit-Recognizer-Competition/KNN-Pure-Python.ipynb)

### Wine Score Predictor
[Wine Score Predictor predicts wines scores based on their description. First, the descriptions are weighted using TF-IDF and then stored as vectors into locality-sensitive hashing engine, where they are stored using random binary projections. Final predictions are made using KNN with distances provided by the LSH engine. I still don't have the final predictions for all the data since it takes so long to compute, but the results have been good with smaller amounts of descriptions so far.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Wine-Score-Predictor/TF-IDF-Pure-Python.ipynb)

# FastAI
### Lesson 1
TODO
