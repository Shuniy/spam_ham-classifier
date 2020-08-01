# [Spam Classifier](https://sms-spam-classifier-zippy.herokuapp.com/)
A Flask application which accepts text from user, and generates prediction whether the text is Spam or Ham.

The data is a collection of SMS messages tagged as spam or ham that can be found [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset). 

*We will implement multiple algorithms such as Naive Bayes, Random Forest Classifier, Bagging Classifier, OneVsRest Classifier and others that [can be found here](https://github.com/ZippySphinx/spam_ham-classifier/blob/master/classifier.ipynb) and then using multiple vectorizers such as CountVectorizer, TfidfVectorizer and Hashing Vectorizer to find the model with best accuracy and metrics. Then, we will select that classifier to make our flask application.*

## Installation
Run the following command on the root directory of project.

**Optional commands to create virual environment to install dependency**:
1. `Create virtual environment: 'python -m venv spamclassifier'`
2. `Activate virual environment: 'spamclassifier\Scripts\activate'`

*To run flask application from virtual environment be in the directory with the server file that is app.py.*

**Command to start server**:
1. `install dependency: 'pip install -r requirements.txt'`
2. `set FLASK_APP=app.py`
3. `flask run`
This will start flask based spam classifier server.

To access home page browse to `http://localhost:5000`

### Packages Used
[Refer to the requirements.txt file.](https://github.com/ZippySphinx/spam_ham-classifier/blob/master/requirements.txt)

### Deployment
[Refer to the this page for deployment steps.](https://devcenter.heroku.com/categories/deployment)
