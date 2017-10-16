<<<<<<< HEAD
### Data Mining (2017 Fall) - Assignment 1
This repository contains all the information for the first assignment of the Data Mining 2017 Fall course. All instructions are posted below. 

**Important Notice:** This is an **individual assignment**, therefore, each student is asked to complete the assignment on their own, following the **Course Academic Integrity Policy** presented in the first session. (Please refer to the orientation handout in the iLMS to learn more about the policy).

**Due Date:** 
The assignment is due on October 16, 2017 (midnight). No extensions will be given for this assignment. Failure to submit assignment on time will result in an automatic score of zero (0). 

---
### Instructions
Please carefully review the following instructions to complete Assignment 1. These instructions assume that you have already created your [GitHub account](https://github.com/), and that you were present in the first lab session. All asignments should be done using `Python 3` and `Jupyter` notebook. 

1. Since all assignments must be submitted, individually by each student, to their GitHub account, you must first `Fork` this repository so that we are able to check your individual submissions through GitHub. If you don't use the `Fork` feature we will not be able to locate your assignment repository.

2. Once you have forked this repository, you can find additional instructions for your assignment in the `hw_1.ipynb` Jupyter notebook. Try to follow each instruction carefully so as to avoid any deductions. 

3. Once you have finished all the tasks in the given notebook, and you are ready to make the final submission, you should change the name of your notebook (`hw_1.ipynb`) to this format (`StudentName_StudentID.ipynb`), and then publish changes to your GitHub forked repository. You can make as much changes to your repository as necessary, since we will check assignments until due date. After due date, you are not allowed to make any more changes to your respositories.

---
### Grading
The following is the grading format for your first assignment.
- 80% - Complete all the tasks given in the provided Jupyter notebook `hw_1.ipynb`.
- 10% - Complete the **bonus exercises** provided in the [first lab session](https://goo.gl/Sg4FS1). Please note that we have updated the notebook so you should be able to find five (6) exercises in the updated version.
- 10% - Creativity and Presentation: For instance, you can present different visualizations and data operations provided in the **Data** handout (Session 1 of Data Mining). (Refer to the iLMS for the handout on **Data**). You can also tidy up your notebook and provide nice explanations or comments where necessary, especially for the new parts you have added. Surprise us! Good Luck!

Questions? Please email TA at (ellfae@gmail.com or eunicebes@gmail.com), or ask us directly on Slack. 

=======
### Lab For Data Mining 2017 Fall @ NTHU
This repository contains all the instructions and necessary code for Data Mining 2017 (Fall) lab session.

---

### Computing Resources
- Operating system: Preferably Linux or MacOS
- RAM: 8GB
- Disk space: Minimum 8GB

---
### Software Requirements
Here is a list of the required programs and libraries necessary for this lab session:
- [Python 3+](https://www.python.org/download/releases/3.0/) (Note: coding will be done strictly on Python 3)
    - Install latest version of Python 3
- [Anaconda](https://www.anaconda.com/download/) environemnt or any other environement (recommended but not required)
    - Install anaconda environment
- [Jupyter](http://jupyter.org/) (Strongly recommended but not required)
    - Install jupyter
- [Scikit Learn](http://scikit-learn.org/stable/index.html)
    - Install `sklearn` latest python library
- [Pandas](http://pandas.pydata.org/)
    - Install `pandas` python library
- [Numpy](http://www.numpy.org/)
    - Install `numpy` python library
- [Matplotlib](https://matplotlib.org/)
    - Install `maplotlib` for python
- [Plotly](https://plot.ly/)
    - Install and signup for `plotly`
- [NLTK](http://www.nltk.org/)
    - Install `nltk` library
---
### Test script
Open a Jupyter notebook and run the following commands. If you have properly installed all the necessary libraries you should see no error.
```python
import pandas as pd
import numpy as np
import nltk
from sklearn.datasets import fetch_20newsgroups
from sklearn.feature_extraction.text import CountVectorizer
import plotly.plotly as py
import plotly.graph_objs as go
import math
%matplotlib inline

# my functions
import helpers.data_mining_helpers as dmh
import helpers.text_analysis as ta
```

---
### Preview of Complete Jupyter Notebook
https://github.com/omarsar/data_mining_2017_fall_lab/blob/master/news_data_mining.ipynb
>>>>>>> 5a28971220c5498cfe696253e3bfaf3420ee05d0
