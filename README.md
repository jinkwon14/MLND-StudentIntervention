# Student Intervention System (Supervised Machine Learning)

As education has grown to rely more on technology, vast amounts of data has become available for examination and prediction. Logs of student activities, grades, interactions with teachers and fellow students, and more, are now captured in real time through learning management systems like **[Canvas](https://www.canvaslms.com/)** and **[Edmodo](https://www.edmodo.com/)**. This is especially true for online classrooms, which are becoming popular even at the primary and secondary school level. Within all levels of education, there exists a push to help increase the likelihood of student success, without watering down the education or engaging in behaviors that fail to improve the underlying issues. Graduation rates are often the criteria of choice, and educators seek new ways to predict the success and failure of students early enough to stage effective interventions.


## Getting started  

### View full report

Full report can be viewed by either clicking this [LINK](https://github.com/kwonjh90/MLND-StudentIntervention/blob/master/student_intervention.ipynb) or clicking on the student_intervention.ipynb file from the committed files list. Please understand that due to the size of data base, loading the report may take a couple of minutes. Thank you for your interest.

### Install

Viewing this project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

### Run

Download or Clone the `MLND-StudentIntervention` projects on to your computer.In a terminal or command window, navigate to the top-level project directory `student_intervention/` (that contains this README) and run one of the following commands:

```bash
ipython notebook student_intervention.ipynb
```  
or
```bash
jupyter notebook student_intervention.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The dataset used in this project is included as `student-data.csv`. This dataset has the following attributes:

- `school` : student's school (binary: "GP" or "MS")  
- `sex` : student's sex (binary: "F" - female or "M" - male)  
- `age` : student's age (numeric: from 15 to 22)  
- `address` : student's home address type (binary: "U" - urban or "R" - rural)  
- `famsize` : family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)  
- `Pstatus` : parent's cohabitation status (binary: "T" - living together or "A" - apart)  
- `Medu` : mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)  
- `Fedu` : father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)  
- `Mjob` : mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")  
- `Fjob` : father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")  
- `reason` : reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")  
- `guardian` : student's guardian (nominal: "mother", "father" or "other")  
- `traveltime` : home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)  
- `studytime` : weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)  
- `failures` : number of past class failures (numeric: n if 1<=n<3, else 4)  
- `schoolsup` : extra educational support (binary: yes or no)  
- `famsup` : family educational support (binary: yes or no)  
- `paid` : extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)  
- `activities` : extra-curricular activities (binary: yes or no)  
- `nursery` : attended nursery school (binary: yes or no)  
- `higher` : wants to take higher education (binary: yes or no)  
- `internet` : Internet access at home (binary: yes or no)  
- `romantic` : with a romantic relationship (binary: yes or no)  
- `famrel` : quality of family relationships (numeric: from 1 - very bad to 5 - excellent)  
- `freetime` : free time after school (numeric: from 1 - very low to 5 - very high)  
- `goout` : going out with friends (numeric: from 1 - very low to 5 - very high)  
- `Dalc` : workday alcohol consumption (numeric: from 1 - very low to 5 - very high)  
- `Walc` : weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)  
- `health` : current health status (numeric: from 1 - very bad to 5 - very good)  
- `absences` : number of school absences (numeric: from 0 to 93)  
- `passed` : did the student pass the final exam (binary: yes or no)
