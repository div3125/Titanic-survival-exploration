# Udacity Machine Learning Engineer Nanodegree
## Optional Exploratory Project
## Titanic Survival Exploration

### Requirements

* Language:- **Python 2.7**

    Python libraries:
    - [NumPy](http://www.numpy.org/)
    - [Pandas](http://pandas.pydata.org)
    - [matplotlib](http://matplotlib.org/)
    - [scikit-learn](http://scikit-learn.org/stable/)

    Additional software:
    
    * [Jupyter Notebook](http://ipython.org/notebook.html) to run IPython notebooks.
    * [Anaconda](http://continuum.io/downloads) distribution for Python 2.7 for above mentioned libraries, if Python is not already installed.

### Code

The original template and supporting files are taken from ```projects/titanic_survival_exploration``` folder of Udacity's  [machine-learning](https://github.com/udacity/machine-learning) repository on GitHub.

Link for Review guidelines: [Titanic Survival Exploration project rubric](https://review.udacity.com/#!/rubrics/147/view)


### Run

In a terminal or command window, navigate to the top-level project directory `titanic_survival_exploration/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook titanic_survival_exploration.ipynb
```
or
```bash
ipython notebook titanic_survival_exploration.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)