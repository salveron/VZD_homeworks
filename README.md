# VZD_homeworks

This repository was created to show my solved homeworks for BI-VZD (Data Mining) subject. Here
is a description for every task:

## 01

The task itself was to download nearly 7,000 pages from the internet, parse and store them in 
tables (aka **web-scraping**). Then we needed to visualize some interesting patterns in the data
using **Python** and its `numpy`, `pandas`, `matplotlib`, `seaborn` and other libraries.

Here is a directory structure:

* `homework_01_B201.ipynb` is a **Jupyter** notebook with the task text in Czech and my complete
solution for it.
* `raw` directory contains the non-parsed web pages in **HTML** that I downloaded from the internet
using Python `requests` library.
* `dataset.csv` contains the useful data from the web pages that I extracted using **Python**
`bs4` library. This dataset is then used to visualize the data in the second part of the task.

## 02

This task was to use different binary classifiers provided by `scikit-learn` library, compare them
and predict the survival of the Titanic passengers. I used four classifiers from `scikit-learn`:
`DecisionTreeClassifier`, `RandomForestClassifier`, `AdaBoostClassifier` and `KNeighborsClassifier`.

The directory structure is here:

* `homework_02_B201.ipynb` is a **Jupyter** notebook with the task text in Czech and my complete
solution for it.
* `data.csv` is a dataset that contains the *survived* column that we needed to predict with the
values from other columns. I used it to train the models, find the best hyperparameters for them
and then test them.
* `evaluation.csv` is a dataset without the *survived* column. The values for the *survived*
attribute is exactly what we needed to predict.
* `results.csv` contains the predicted values for *survived* attribute for Titanic passengers
whose data was stored in `evaluation.csv` file.

## 03

This task was to play with the e-shop customers dataset and `sklearn.cluster.KMeans` algorithm.
As the task demanded, I trained the models using different versions of the same dataset (scaled,
modified and scaled modified ones) and compared the results.

The directory structure is quite simple:

* `homework_03_B201.ipynb` is a **Jupyter** notebook with the task and my solution.
* `esop.csv` is a .csv dataset that we needed to work with. To extract the data about the customers,
we needed to aggregate the given data by their ID and compute some interesting values.
