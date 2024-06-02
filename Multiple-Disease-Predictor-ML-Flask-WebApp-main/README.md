# Disease-Predictor-ML-Flask-WebApp 

It's an end-to-end Machine Learning Project. The purpose of this project is to predict whether a person is suffering from a particular disease or not on the basis of his/her input data. The prediction has been done by using Machine Learning (ML) classification algorithms. Currently, this web app can predict 3 types of diseases (Diabetes, Parkinson's and Heart Disease). 


### Install

This project requires **Python** and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- Seaborn
- scikit-learn
- Flask

### How this project has been created

**Step-1** : Build and trained ML models for each of the 3 diseases, whose code is written in the `diabetes.py`, `heart.py` and `parkinsons.py` files and saved the model in pickle file `diabetes.pkl`, `heart.pkl`, and `parkinsons.pkl` respectively.

**Step-2** : Created Flask web app whose code is written in `app.py` file. For the interactive user interface, HTML and CSS have been used. HTML files are stored in `templates` directory while CSS files and web app's background image is stored in `static` directory.

