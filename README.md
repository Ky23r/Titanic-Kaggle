<h1 align="center"> Titanic - Machine Learning from Disaster </h1>

***Titanic Survival Prediction***

This project implements a machine learning model to predict the survival of passengers on the Titanic. The model was built and trained using various techniques, including data preprocessing, feature engineering, and logistic regression. It achieved a score of 0.76315 on the Kaggle competition.

***Introduction***

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. The goal of this project is to predict whether a passenger survived the disaster using a dataset containing information about the passengers, such as their age, sex, class, and fare. This project applies machine learning techniques to analyze the data and make predictions.

***Dataset***

The dataset provided by Kaggle includes the following features:

- **PassengerId**: A unique identifier for each passenger.
- **Pclass**: The passenger's class (1st, 2nd, or 3rd).
- **Name**: The name of the passenger.
- **Sex**: The gender of the passenger.
- **Age**: The age of the passenger.
- **SibSp**: The number of siblings or spouses aboard the Titanic.
- **Parch**: The number of parents or children aboard the Titanic.
- **Ticket**: The ticket number.
- **Fare**: The fare paid by the passenger.
- **Cabin**: The cabin number.
- **Embarked**: The port where the passenger boarded the Titanic.

The dataset is divided into a training set with 891 entries and a test set with 418 entries.

***Requirements***

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

***Run the Application***

After installing the necessary libraries, you can run the application using the following command:

```bash
jupyter notebook Titanic_Kaggle.ipynb
```

***Model Architecture***

The model used in this project is a Logistic Regression model with the following characteristics:

- **Solver**: 'liblinear', chosen for its efficiency with small datasets.
- **Max Iterations**: 1000, to ensure convergence.

***Results***

The model achieved an accuracy score of 0.76315 on the Kaggle public leaderboard. This result reflects the effective use of data preprocessing and feature engineering techniques in conjunction with logistic regression to predict passenger survival.
