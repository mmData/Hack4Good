**Introduction:**  
Welcome to the GitLab Repo for the Pilot edition of Hack4Good this FS19.  
Hack4Good is a 5-week long pro-bono program that matches Data Science talents from ETH Zurich with organisations (NGOs) that promote social causes. In close collaboration with such a NGO, small teams of 3-4 students develop and implement data-driven solutions to increase these organizations' impact.


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
├── notebooks                <- Jupyter notebooks. Every developper has its own folder for exploratory
│   ├── name                    notebooks. Usually every model has its own notebook where models are
│   │   └── exploration.ipynb   tested and optimized. (The present notebooks can be deleted as they only serve for inspiration purposes)
│   └── model
│       └── model_exploration.ipynb <- different optimized models can be compared here if preferred    
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
│
├── scores                   <- Cross validation scores are saved here. (Automatically generated)
│   └── model_name           <- every model has its own folder.
│
├── src                      <- Source code of this project. All final code comes here (Notebooks are thought for exploration)
│   ├── __init__.py          <- Makes src a Python module
│   ├── main.py              <- main file, that can be called.
│   │
│   │
│   └── utils                <- Scripts to create exploratory and results oriented visualizations
│       └── exploration.py      / functions to evaluate models
│       └── evaluation.py       There is an exemplary implementation of these function in the sample notebook and they should be seen
                                as a help if you wish to use them. You can completely ignore or delete both files.
```



* delete the env to recreate it when too many changes are done  

  ```conda env remove -n env_your_proj```
