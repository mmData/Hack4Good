**The Hack4Good Project:**  
Welcome to the GitLab Repo for the Pilot edition of Hack4Good this FS19. This is the Repo of team Red composed by Marco Mancini, Yilmazcan Ozyurt, Ylli Muhadri and Maria R. Cervera. 

Hack4Good is a 5-week long pro-bono program that matches Data Science talents from ETH Zurich with organisations (NGOs) that promote social causes. In close collaboration with such a NGO, small teams of 3-4 students develop and implement data-driven solutions to increase these organizations' impact.

**Introduction:** 

A decade ago, an armed conflict led to a humanitarian crisis
in the North-East of Nigeria, which lasts until today. The crisis
has caused the displacement of millions of civilians, and it is
estimated that seven million people are in need of humanitarian
assistance. In this context, REACH conducted in 2017 a Multisectorial Needs Assessment identifying the needs for internally
displaced peoples, returnees and non-displaced peoples. This
dataset, which combines information on a variety of sectors
including Food, Education, Health etc. offers unique potential to
investigate underlying relationships between the characteristics
of the people and their needs, ultimately helping decisionmaking for humanitarian aid. Here, we tried to further explore
this dataset and uncover patterns so far not identified.

**Methods:** 
Datasets were provided by REACH. Analyses were done with
Python 3.5 using numpy, pandas, scikit-learn, yellowbrick
The ultimate goal of this project is assesing whether demographic variables 
can be good predictors for needs of the population an whether these needs are related
between each other.
We then
tried two approaches: predictive models and clustering. Several
predictive models were tested, from simple linear classifiers
to complex ensemble and boosting methods. We focused on
Balanced Random Forest (BRF), which if well suited for tasks
with imbalanced classes. For clustering the HHs according
to their demographics, we used Gower dissimilarity measure
[1] to introduce the dissimilarity matrix of HHs based on the
features, and then applied Constant Shift Embedding (CSE)
[2] to project our matrix into 2D space for visualization.

**Useful Links:**
*  [Impact Initiatives website](http://www.impact-initiatives.org/)

**Workshop Dates:**

| Event | Date | Location |
| ------ | ------ | ------ |
| Teamwork time in the SPH (optional) |  24.4.19 (Wed) , 17:00 - 19:00| SPH |
| Workshop 1: Agile workshop for Data Science by external experts | 26.4.19 (Fri), 16:30 - 20:30 | HG E.42 |
| Teamwork time in the SPH (optional) | 29.4.19 (Mon), 17:00 - 19:00 | SPH |
| Workshop 2: Feedback workshop | 8.5.19 (Wed), 17:00 - 19:00 | SPH |
| Workshop 3: Pitching workshop | 15.5.19 (Wed), 17:00 - 19:00 | SPH |
| Final event: Final presentation & Workshop 4: Reflection | 20.5.19 (Mon), 17:30 - 21:30 | SPH |



**Folder Structure**




```
├── LICENSE
│
│
├── README.md                <- The top-level README for developers using this project
│
├── environment.yml          <- Python environment
│                               
│
├── data
│   ├── processed            <- The final, canonical data sets for modeling.
│   └── raw                  <- The original, immutable data dump.
│
│
├── misc                     <- miscellaneous
│
│
├── notebooks                <- Jupyter notebooks used to perform the analysis. They include initial manipulation of the data, ML model
|                               and clustering. The README file in this folder has a more detailed explanation of each file.
│
│
├── reports                   <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures               <- Generated graphics and figures to be used in reporting
│
│
├── results
│   ├── outputs
│   └── models               <- Trained and serialized models, model predictions, or model summaries
│                               (if present)

```




