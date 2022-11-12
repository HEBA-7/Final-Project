# Final Project- "Happy Tool"



### Proposal and delivery: create an interactive tool/dashboard with new KPI's to users for exploring and extract their own conclusions.

**This is the final project for Ironhack Data Analytics- V.0**

This model data has 3 dataset:

    1. Happiness rank by country (2015- 2019)
    
    2. Suicide rate by country (every 100000 population)
    
    3. Daylight by country (in some countries I calculate de avg- for the different timetable)

   ![Image](emoticon-cara-sonriente-graffiti-rociado-aislado-sobre-fondo-blanco-ilustracion-vectorial_36380-425.webp)

---

### :computer: **Technology stack**
- Pandas

- Python

- Jupyter

- Tableau

### :boom: **Core technical concepts and inspiration**
The dashboard of "Happy Tool" offers you an analytical report with data about:

- Map of Happiness and Suicide Rate
- Evolution of Happiness and Suicide Rate by Year
- Suicide Rate by Country and Gender
- Correlation Happiness and Suicide Rate
- Daylight by Country
- Rank Happiness by Country (Suicide Rate and Daylight)
- Resume: with Top Rank countries, a New Rank by country and Avg. Differences rate by gender


### :wrench: **Configuration**

import pandas as pd

import numpy as np

import functools as ft

import seaborn as sns

import matplotlib.pylab as plt

### :see_no_evil: **Usage**

The Dashboard is interactive, so depending on the window you are you can filter by country, year, gender etc...

[Dashboard](https://public.tableau.com/app/profile/halima8505/viz/HappyToolPresentation/HappyTool?publish=yes)



### :file_folder: **Structure**


![Image](architecture)


```
└── Final-Project
    ├── data
    │   ├── 2015.csv
    │   ├── 2016.csv
    │   ├── 2017.csv
    │   ├── 2018.csv
    │   ├── 2019.csv
    │   ├── sunshine hours by city.csv
    │   └── suicide.csv
    ├── img
    │
    ├── mini_eda.ipynb
    ├── mini_eda-sun.ipynb
    ├── first_dataset.csv
    ├── happy_suicide_daylight.csv
    ├── happy_gender_daylight.csv
    ├── README.md
    └── .gitignore
``` 

### :information_source: **Further info**
- [Happiness scored by country](https://www.kaggle.com/datasets/unsdsn/world-happiness)
- [Suicide rate](https://www.who.int/data/gho/data/themes/mental-health/suicide-rates)
- [Horas de luz](https://www.kaggle.com/datasets/prasertk/sunshine-duration-by-city?resource=download)

