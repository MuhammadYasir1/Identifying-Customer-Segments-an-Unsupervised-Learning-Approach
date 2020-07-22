# Identifying-Customer-Segments-an-Unsupervised-Learning-Approach
Clustering Techniques using Sickit learn to Identify Customer Segments

## Table of Contents

1. [Installation](#installation)
2. [Run](#Run)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation <a name="installation"></a>
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend users install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.
### Run

In a terminal or command window, navigate to the top-level project directory `Identifying_Customer_Segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Identifying_Customer_Segments.ipynb
```  
or
```bash
jupyter notebook Identifying_Customer_Segments.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Project Motivation<a name="motivation"></a>

This is the third project of Udacity Data Scientist Nanodegree. In this project, I applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns.


### File Descriptions <a name="files"></a>

There is one iPython notebook to showcase work related to this project. 
The html file was generated from iPython notebook to submit this project.

### Results<a name="results"></a>

Cluster 4 is overrepresented in the customers data compared to general population data. Some characteristics of the group of population that are relative popular with the mail-order company:

* in areas where the share of 6-10 family homes is lower (PLZ8_ANTG3=1.73)
* in Prosperous or Comfortable households (WEALTH=2.75)
* in life stage of Families With School Age Children or Older Families & Mature Couples (LIFE_STAGE=3.30)

Cluster 13 is underrepresented in the customers data. Some characteristics of the segment of the population that are relatively unpopular with the company:

* in areas where the share of 6-10 family homes is higher (PLZ8_ANTG3=2.44)
* in Less Affluent or Poorer households (WEALTH=4.4)
* in life stage of Pre-Family Couples & Singles or Young Couples With Children (LIFE_STAGE=1.98)


### Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data was provided by Udacity partners at Bertelsmann Arvato Analytics.
