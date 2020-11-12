# Nihal_Portfolio
Data science portfolio.

# [Project 1: Spiritual person classifier: Project overview](https://github.com/Nihal72/ImageClassification)

## Live at [Click here to use.](https://spirtual-being-classifier-v3nv.herokuapp.com/)
* Developed an end-to-end image classifier, it can Predict the name of 9 Spiritual being based on their image. 
* Over 1000 images were collected from google images by performing web scraping using python.
* Data cleaning and face detection was performed using Haar-cascade in OpenCV. 
* To prevent overfitting, I used 10-fold cross-validation, Random Forest Classifier was used to train the model and to find the best parameters I have used GridSearchCV       algorithm, which was 92% accurate.  
* By doing Error analysis, F-1 score was found low for those persons which have low variety of images and contains noise in the images, model was giving false predictions sometimes for similar looking persons like Sadhguru and Osho. 
* Build an interactive Web app  using streamlit.  
* Web app was deployed to production using heroku. 
