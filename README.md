# Nihal_Portfolio
Data science portfolio.

# [Project 1: Spiritual person classifier: Project overview](https://github.com/Nihal72/ImageClassification)

## Live at ➥ [Click here.](https://spirtual-being-classifier-v3nv.herokuapp.com/)
* Developed an end-to-end _**image classifier**_, it can Predict the name of _**9 Spiritual being**_ based on their image. 
* Over 1000 images were collected from _**google images**_ by performing _**web scraping using python.**_
* Data cleaning and _**face detection**_ was performed using _**Haar-cascade in OpenCV.**_ 
* To prevent _**overfitting**_, I used _**10-fold cross-validation**_, _**Random Forest Classifier**_ was used to train the model and to find the best parameters I have used   _**GridSearchCV**_ algorithm, which was _**92% accurate.**_  
* By doing _**Error analysis**_, _**F-1 score**_ was found low for those persons which have _**low variety of images and contains noise in the images**_, model was giving false predictions sometimes for _**similar looking persons**_ like Sadhguru and Osho. 
* Build an interactive _**Web app**_  using _**streamlit.**_  
* Web app was deployed to _**production**_ using _**heroku.**_ 
