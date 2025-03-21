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


The ultimate goal of this project is assesing whether demographic variables 
can be good predictors for needs of the population an whether these needs are related
between each other.
We then tried two approaches: predictive models and clustering. Several
predictive models were tested, from simple linear classifiers
to complex ensemble and boosting methods. We focused on
Balanced Random Forest (BRF), which is well suited for tasks
with imbalanced classes. For clustering the Households according
to their demographics, we used Gower dissimilarity measure
 to introduce the dissimilarity matrix of Households based on the
features, and then applied Constant Shift Embedding (CSE)
to project our matrix into 2D space for visualization.





**Requirements:** 


Datasets were provided by REACH and can be found in the folder data/raw. Analyses were done with
Python 3.5 using numpy, pandas, scikit-learn, yellowbrick



**Useful Links:**
*  [Impact Initiatives website](http://www.impact-initiatives.org/)




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




