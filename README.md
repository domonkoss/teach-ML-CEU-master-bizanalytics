

## Machine Learning #1 and #2


This repo contains materials for the introductory/intermediate Machine Learning (ML) courses (3 credits total) taught in the
[MSc in Business Analytics program](https://economics.ceu.edu/program/master-science-business-analytics)
at the Central European University (CEU), 2019.
The material for 2018 can be found on branch '2018'.
The material for the previous 2-credit course taught in 2016 and 2017 can be found
[here](https://github.com/szilard/teach-data-science-msc-analytics-ceu).

### Course Design and Instructors

Zoltán Papp <br>
Jenő Pál (TA)

### Initial Course Designer (and Instructor pre-2018):

Szilárd Pafka <br>

### Course Description and Objectives

The breakdown below (into ML #1 an #2) is somewhat adhoc and mainly to comply with administrative requirements.
Both courses will intertwine general ML concepts, algorithms and software implementations/tools and will
aim to strike a balance of theory and practice with the goal of equiping students with both the
foundations to understand the ML methodology and also with the skills needed for using ML in practical
business applications.

#### Data Science and Machine Learning 1 (Concepts):

After an overview of the entire data science landscape this course will focus on machine learning. The course will introduce the main fundamental concepts in machine learning (supervised learning, training, scoring, accuracy measures, test set, overfitting, cross validation, model capacity, hyperparameter tuning, grid and random search, regularization, ensembles, model selection etc.) The concepts will be illustrated with R code therefore it requires prior familiarity with R.

#### Data Science and Machine Learning 2 (Tools):

This course will build on the previous one (which introduced the basic concepts in machine learning) and will discuss state-of-the-art algorithms for supervised learning (linear models, lasso, decision trees, random forests, gradient boosting machines, neural networks, support vector machine, deep learning etc.). A large part of the course will be dedicated to using (hands-on) the software tools for machine learning used by data scientists in practice (various high-performance R packages, xgboost, libraries for deep learning etc.).


### Grading

- 45% Weekly Assignments (homework exercises). These will be submitted using Moodle.
- 45% Final Exam
- 10% Quizzes at the beginning of each lecture, except the first lectures of each course. Missing a lecture or being late will result in 0% for the actual quiz score.

(each course ML #1 and #2 separately)

Weekly assignment dates and deadlines for ML #1:
- Jan 16, due on Jan 29 8:00 AM
- Jan 23, due on Feb 5 8:00 AM
- Jan 30, due on Feb 12 8:00 AM

Weekly assignment acceptance policy and achievable grades:
- 100% until due date
- 50% within 24 hours past due date
- 0% after that.


### Announcements and Q&A

Class announcements and student Q&A will be done via Moodle


### Syllabus and Schedule:

### ML #1

**ML 1.1:** Overview of data science. The elements of a data science project. Data preparation. Exploratory data analysis, data visualization. Machine learning. Workflow, reproducibility and productivity.
[Lecture](ml.1.1/lect) | [Lab](ml.1.1/lab).

**ML 1.2:** Introduction to supervised learning. Linear models vs k-nearest neighbors. Training and test error. Validation set. Bias and variance. Model evaluation and selection. Benchmark model selection. Boostraping, resampling. Time series split up by time.
[Lecture](ml.1.2/lect) | [Lab](ml.1.2/lab).

**ML 1.3:** A high-level introduction to RF, Lasso, SVM, Boost, NN. Overfitting, regularization, cross-validation, naive implementation. ROC curve, AUC. Calibration plot. Hyperparameter tuning, grid, and random search.
[Lecture](ml.1.3/lect) | [Lab](ml.1.3/lab).

**ML 1.4:** Unsupervised learning. Clustering (k-means, hierarchical). PCA / ICA. Time Series Analysis: correlation, autocorrelation, Filtering. Reviewing best practices in data science and practical research.
[Lecture](ml.1.4/lect) | [Lab](ml.1.4/lab).


### ML #2

**ML 2.1:** Deeper understanding of linear models, lasso. Understanding and tuning parameters for trees, random forests and gradient boosting machines. Impact of correlated features. Support vector machines.
Tools: R packages, xgboost, lightgbm
[Lecture](ml.2.1/lect) | [Lab](ml.2.1/lab).

**ML 2.2:** Neural networks and deep learning. Reinforcement Learning. Evolutionary Computing.
Tools: R packages, Keras.
[Lecture](ml.2.2/lect) | [Lab](ml.2.2/lab).

**ML 2.3:** Ensembles, Stacking. Deploying machine learning models to production.
[Lecture](ml.2.3/lect) | [Lab](ml.2.3/lab).

**ML 2.4:** Recap and summary. **Final Exam (ML #1 and #2).**
[Lecture](ml.2.4/lect) | [Lab](ml.2.4/lab).





