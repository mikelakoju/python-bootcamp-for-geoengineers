![python-bootcamp-for-geoengineers-logo](https://user-images.githubusercontent.com/51282928/83759266-80d8f580-a69d-11ea-9149-9c2eed8b025f.png)

Python Bootcamp for Geoengineers is a GitHub repository that stores all of available materials to start learning and working with Python for needs in oil and gas exploration and production, energy sector, and geoscience. This repo also stores all Jupyter notebooks that I give training to several SPEs student and professional sections. Some materials also linked to other repos and packages that I created (e.g. *PyReservoir* and *PyReSim*) where they're used.

## Contents:
* **Workshops and Training**

  * [Introduction to Python for Exploration and Production Course](https://github.com/yohanesnuwara/python-bootcamp-for-geoengineers#1-introduction-to-python-for-exploration-and-production-course-notebook) 
  * [Geoscience, Exploration, and Production Automation with Python](https://github.com/yohanesnuwara/python-bootcamp-for-geoengineers#2-geoscience-exploration-and-production-automation-with-python)
 
* **Talks**

  * [Python Awareness in Exploration and Production for Students and Professionals](https://github.com/yohanesnuwara/python-bootcamp-for-geoengineers#1-python-awareness-in-exploration-and-production-for-students-and-professionals-notebook)


## Workshops and Training

### 1. Introduction to Python for Exploration and Production Course ([Notebook](https://colab.research.google.com/drive/1NKjTuP16JeX8a1lvS2bRaqSCEnhGzFZD?usp=sharing))

This is a 1-day (3-hour) workshop I gave with SPE Trisakti Student Chapter, Indonesia, in September 13rd, 2020. Around 450 participants registered for this training session. 

[<img src="https://user-images.githubusercontent.com/51282928/91654109-81343180-ead0-11ea-898d-4c43c199fa14.png">](https://colab.research.google.com/drive/1NKjTuP16JeX8a1lvS2bRaqSCEnhGzFZD?usp=sharing)

**Topics discussed:**

*To start learning the following curriculum, see inside the notebook link provided above.* 

* Very Brief Intro to Numpy, Matplotlib, Pandas, and Scipy
* Python for Exploration
  * Streaming well log and seismic data from open geoscience data
  * Visualize well log data
  * Basic exploratory data analysis (crossplot and histogram) using Seaborn
  * Basic petrophysics processing (computation of porosity, Vclay)
  * Demo: Read and display 3D seismic data
* Python for Production
  * Streaming production data (borehole pressure, production rate)
  * Simple well-test analysis
  * Simple decline curve analysis

### 2. Geoscience, Exploration, and Production Automation with Python (Go to [Folder]())

This is a 5-day (2-hour) training I (and Destiny Otto) gave with SPE Port Harcourt Section in Nigeria, from 6 to 21 November 2020. Surprisingly, 1,000+ participants from academia and industry from all around the world registered for this training session. 

In the folder, you will find 5 notebooks (3 notebooks for training + 2 for assignments; answer key).

**Topics discussed:**

* Formation evaluation with Python: Dataset used is well 15/9-F-11 A in Volve field dataset
  * Visualize well log data
  * Visualize triple combo
  * Visualize Neutron-Density plot
  * Compute petrophysical variables (formation porosity PHIF, shale volume VSH, and permeability K)
  
* Material balance analysis with Python: Using [`PyReservoir`](https://github.com/yohanesnuwara/pyreservoir). Datasets used are from `PyReservoir` tutorial notebooks, and in Volve field dataset
  * Produce MBAL plot to calculate OOIP and OGIP in gas and oil reservoirs
  * Calculate water (aquifer) influx
  
* Well-test analysis with Python: Using [`PyReservoir`](https://github.com/yohanesnuwara/pyreservoir). Datasets used is well 15/9-F-1 C in Volve field dataset
  * Simulation of constant rate and pressure test
  * Analysis of BHP drawdown and build-up 

## Talks

### 1. Python Awareness in Exploration and Production for Students and Professionals ([Notebook](https://github.com/yohanesnuwara/python-bootcamp-for-geoengineers/blob/master/demo_starting_python_E%26P_1hour.ipynb))

This is my 1-1.5 hour talk to tell reasons why geoscientists and petroleum engineers, students and professionals, should consider starting to learn Python. I gave this talk in a joint webinar by SPE Asia Pacific University (Malaysia) and SPE Northern Emirates Section (UAE) in 21 October, 2020. 

I gave a Python demo as a trigger material. See inside the notebook.

* Python and its effectiveness - *comparing use vs. non-use of list comprehension*
* Numpy, Matplotlib, and Pandas - *quick tour of the libraries*
* Access exploration open dataset - *stream exploration data (well log) from Kansas Geological Survey*
* Access production open dataset - *stream production data from Volve field in a Zenodo repository*

### 2. Machine Learning Application in the Volve Field Dataset

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

<!--
**yohanesnuwara/yohanesnuwara** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

**Python Bootcamp for Geoengineers** was created in June 2020, seeing lots of geoengineers and geoscientists are interested to start programming in Python. This Bootcamp is structured into **4 Courses** and **1 Demo Room** (so far), each of the courses contains several modules that can be accessed using **Google Colab**, a web-cloud Python IDE. 

It is always recommended to start with the first 2 courses (**Intro to Python I and II**). Then, you could choose either to take the **Python Course for Oil and Gas** (ideal for geoengineers, such as petroleum engineers or reservoir engineers) or to take the **Python Course for Geoscience** (ideal for geoscientists, such as geologists or geophysicists). 

At the end of each course, there is a dummy **Exam** to test how far you already master each course!

Enjoy!


## Intro to Python I (Absolute Beginner)

1. Intro to Google Colab
2. [Intro to Numpy](https://colab.research.google.com/drive/1C2RCLJCQcyjw3pdfjWpQgOwCQWvHbqJs?usp=sharing)
3. Intro to Visualization with Matplotlib
4. Intro to Data with Pandas
5. Exam

## Intro to Python II (Next Level)

5. Intro to Scientific Computing with Scipy
6. Intro to Exploratory Data Analysis with Seaborn
7. Exam

## Python Course for Oil and Gas

1. Exploring Production Data with Pandas
2. Plotting Production with Matplotlib
3. Decline Curve Analysis with Scipy
4. Volumetric Calculation in Python
5. Exam

## Python Course for Geoscience

1. Accesing Open Geoscience Data
2. Well-log Data Processing and Petrophysics
3. Exploring Seismic Data
4. Exam
