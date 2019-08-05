## Titanic Survival Exploration
One of the most infamous and tragic shipwrecks in history was the sinking of the RMS Titanic. According to the survivors and the available evidence, one of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

The power of machine learning can be used to predict which passengers were likely to survive the disaster. In order to find the most efficient machine learning algorithm to do that, I analyzed different machine learning algorithms like naive bayes, decision tree, logistic regression, support vector machines, k nearest neighbors, perceptron algorithm, stochastic gradient descent, random forest. The decision tree classifier, SVM and random forest classifier were among the algorithms having high accuracy on the titanic dataset.

### Data
The titanic dataset contains data of 891 passengers. There are 11 features present in the data for each passenger on the ship:

*   Survived: Outcome of survival (0 = No; 1 = Yes)
*   Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
*   Name: Name of passenger
*   Sex: Sex of the passenger
*   Age: Age of the passenger (Some entries contain NaN)
*   SibSp: Number of siblings and spouses of the passenger aboard
*   Parch: Number of parents and children of the passenger aboard
*   Ticket: Ticket number of the passenger
*   Fare: Fare paid by the passenger
*   Cabin Cabin number of the passenger (Some entries contain NaN)
*   Embarked: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

### Softwares and Libraries

* [Python 2.7 or higher](www.python.org)
* [Jupyter Notebook](http://ipython.org/notebook.html)
* [Scikit-learn](https://pypi.org/project/scikit-learn/)
* [NumPy](https://pypi.org/project/numpy/)
* [Pandas](https://pypi.org/project/pandas/)

### How to get the project files
1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/adityasaxena26/titanic-survival-exploration.git
cd titanic-survival-exploration
```
2. Run the following to open up the Jupyter notebook server:
`jupyter notebook`

3. In the browser, open the notebook ```titanic_survival_model.ipynb```
