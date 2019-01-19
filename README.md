# ML-Junkyard
![picture alt](https://imgs.xkcd.com/comics/machine_learning.png)

# Contents
* Projects
    * [Fashionizer](https://github.com/nameisxi/ML-Junkyard/#fashionizer)
* Models
    * Image Recognition
        * [Clothing Classifier (CNN - 94.05%)](https://github.com/nameisxi/ML-Junkyard/#clothing-classifier-cnn---9405)
    * Natural Language Processing
        * [Wine Score Predictor](https://github.com/nameisxi/ML-Junkyard/#wine-score-predictor)
* Kaggle Competitions
    * [House Price Prediction (Simple decision tree - 18K USD)](https://github.com/nameisxi/ML-Junkyard/#house-price-prediction-simple-decision-tree---18k-usd)
    * [House Price Prediction (Random forest - 10K USD)](https://github.com/nameisxi/ML-Junkyard/#house-price-prediction-random-forest---10k-usd)
    * [Digit Recognizer (KNN - 97.07%)](https://github.com/nameisxi/ML-Junkyard/#digit-recognizer-knn---9707)
* Exercises (Textbooks)
    * [An Introduction to Statistical Learning]()
    * [Hands-On Machine Learning]()  
    

# Projects
## Image Recognition
### Fashionizer
[Fashionizer is a web app with Flask backend that uses my Clothing Classifier model to predict the apparel type in uploaded image.
Preprocessing includes turning uploaded image into 28x28 MNIST image that resembles images from the Fashion MNIST, on which Clothing Classifier has been trained on.](https://github.com/nameisxi/Fashionizer)
    


# Models
## Image Recognition
### Clothing Classifier (CNN - 94.05%)
[CNN that's been trained on the Fashion MNIST dataset. Includes multiple versions implemented on Keras and FastAI.](https://github.com/nameisxi/ML-Junkyard/tree/master/Models/Clothing-Classifier)

## Natural Language Processing
### Wine Score Predictor
[Wine Score Predictor predicts wines scores based on their description. First, the descriptions are weighted using TF-IDF and then stored as vectors into locality-sensitive hashing engine, where they are stored using random binary projections. Final predictions are made using KNN with distances provided by the LSH engine. This project is on hold until I have time to address the problematic scaling of TF-IDF. It turns out that 130k descriptions take a long time to compute using TF-IDF and for the time being I feel like I already accomplished everything I wanted in terms of understanding and implementing TF-IDF.](http://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Models/Wine-Score-Predictor/TF-IDF-Pure-Python.ipynb)







# Kaggle Competitions
### House Price Prediction (Simple decision tree - 18K USD)
[This was my first machine learning exercise, and well, it probably seems like it. The exercise was pretty structured, but I tried to make mine a bit different and experiment on the go, as often as possible. My solution only uses a simple decision tree to make the house price predictions, but I think that it turned out to be just fine, even though there is some room for improvement.](https://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle-Competitions/Housing-Prices-Prediction-Exercise/Kaggle-House-Price-Prediction-Exercise.ipynb)

### House Price Prediction (Random forest - 10K USD)
[This was my first Kaggle competition submission, and it's basically only an improved version of my earlier house price prediction exercise. This time instead of decision trees I decided to use random forest regressor, and it turned out to lower the error from 18K USD to roughly 10K USD.](https://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle-Competitions/Housing-Prices-Prediction-Competition/Kaggle-House-Price-Prediction-Competition-Solution.ipynb)

### Digit Recognizer (KNN - 97.07%)
[This is my first picture classification competition and I decided to use KNN mainly because I wanted to understand the algorithm well. CNN's definitely perform better, but I felt the need to understand KNN first. Final accuracy score with this pure Python implementation is 97.07%.](https://nbviewer.jupyter.org/github/nameisxi/ML-Junkyard/blob/master/Kaggle-Competitions/Digit-Recognizer-Competition/KNN-Pure-Python.ipynb)
