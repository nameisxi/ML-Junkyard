# ML-Junkyard
![picture alt](https://imgs.xkcd.com/comics/machine_learning.png)

# Contents
* Kaggle
    * [House Price Prediction Exercise](https://github.com/nameisxi/ML-Junkyard/#house-price-prediction-exercise)
    * [House Price Prediction Competition](https://github.com/nameisxi/ML-Junkyard/#house-price-prediction-competition)
    * [Digit Recognizer Competition](https://github.com/nameisxi/ML-Junkyard/#digit-recognizer-competition)
    * [Wine Score Predictor](https://github.com/nameisxi/ML-Junkyard/#wine-score-predictor)
* Fast.ai Deep Learning Part 1
    * [Lesson 1: Image Recognition](https://github.com/nameisxi/ML-Junkyard/#lesson-1-image-recognition)
    * [Lesson 2: Convolutional Neural Networks](https://github.com/nameisxi/ML-Junkyard/#lesson-2-convolutional-neural-networks)
    
# Kaggle 
### House Price Prediction Exercise
[This was my first machine learning exercise, and well, it probably seems like it. The exercise was pretty structured, but I tried to make mine a bit different and experiment on the go, as often as possible. My solution only uses a simple decision tree to make the house price predictions, but I think that it turned out to be just fine, even though there is some room for improvement.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Housing-Prices-Prediction-Exercise/Kaggle-House-Price-Prediction-Exercise.ipynb)

### House Price Prediction Competition
[This was my first Kaggle competition submission, and it's basically only an improved version of my earlier house price prediction exercise. This time instead of decision trees I decided to use random forest regressor, and it turned out to lower the error from 18K USD to roughly 10K USD.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Housing-Prices-Prediction-Competition/Kaggle-House-Price-Prediction-Competition-Solution.ipynb)

### Digit Recognizer Competition
[This is my first picture classification competition and I decided to use KNN mainly because I wanted to understand the algorithm well. CNN's definitely perform better, but I felt the need to understand KNN first. Final accuracy score with this pure Python implementation is 97.07%.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Digit-Recognizer-Competition/KNN-Pure-Python.ipynb)

### Wine Score Predictor
[Wine Score Predictor predicts wines scores based on their description. First, the descriptions are weighted using TF-IDF and then stored as vectors into locality-sensitive hashing engine, where they are stored using random binary projections. Final predictions are made using KNN with distances provided by the LSH engine. This project is on hold until I have time to address the problematic scaling of TF-IDF. It turns out that 130k descriptions take a long time to compute using TF-IDF and for the time being I feel like I already accomplished everything I wanted in terms of understanding and implementing TF-IDF.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle/Wine-Score-Predictor/TF-IDF-Pure-Python.ipynb)

# Fast.ai Deep Learning Part 1
### Lesson 1: Image Recognition
[Exercises](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Fast-AI/lesson1-exercises.ipynb)
### Lesson 2: Convolutional Neural Networks
TODO
