# Iris flowers Analysis and Species Identification #

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/iris-flowers/blob/master/notebook.ipynb)&nbsp;[![Open in Kaggle](https://www.kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/jofaval/iris-flower-analysis-and-species-identification)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objective](#-objective)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data
[↑ Back to the table](#table-of-contents)

The data is available at the following link:\
[https://www.kaggle.com/datasets/arshid/iris-flower-dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

Being it's official link:
[https://archive.ics.uci.edu/ml/datasets/iris](https://archive.ics.uci.edu/ml/datasets/iris)

## 📓 Description
[↑ Back to the table](#table-of-contents)

The Iris flower data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems. It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. The data set consists of 50 samples from each of three species of Iris (Iris Setosa, Iris virginica, and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.

## ✔️ Objectives
[↑ Back to the table](#table-of-contents)

Testing different machine learning multi-label classification techniques as to predict the species of an iris flower (setosa, versicolor and virginica).

## 🧱 Tech stack
[↑ Back to the table](#table-of-contents)

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- Scikit-Learn, the library used for Machine Learning and statistics models: Linear Regression, SVR, Lasso, Ridge, etc.

## 💹 Algorithms
[↑ Back to the table](#table-of-contents)

I just wanted to try out how different algorithms would perform with this dataset, leaving the Support Vector Machine for last (the recomended one).

I've used: Logistic Regression, XGBoost, Random Forest, Decision Trees, K-Nearest Neighbors, the aforementioned Support Vector Machine and LightGBM (similar to XGBoost, kind of, but open-sourced by Microsoft).

They all performed as expected, as in, XGBoost did perform better than Logistic Regression, while the latter not being too far off, Random Forest did performed "worse", but it's a matter of seed, but I did wanted to stick to one seed just to focus on applying the right techniques rather than a high score. LightGBM did shocked a little by not performing similarly to XGBoost, in fact, it performed the worst from them all, but, again, a matter of the random seed, mostly.

## 📊 Visualization
[↑ Back to the table](#table-of-contents)

Here there weren't too many features, just four, and they were all cleaned and without any missing value whatosever, so the main pair of visualizations here are the simple scatterplots that identify the "clusters", so to say, of the different species, by sepal and petal, being petal the one that more clearly helps identify each species on a plot.

## 🤓 Conclusions
[↑ Back to the table](#table-of-contents)

At times may be boring, but history promises to, at least, always teach you something new, or the origins of something you knew from long. I'm seeing a lot of researches and papers being published publicly, a lot of data to play with, and it's nice to see it's a "tradition" that did start long ago.

As for the machine learning models and techniques, it is a perfect dataset, there was no surprise here about it, but it did allowed for a little bit of playground for some models and tuning. As well as plotting and visually identifying labels with the help of markers.

## ©️ Credits
[↑ Back to the table](#table-of-contents)

From R.A. Fisher, 1936. Also known as Ronald Aylmer Fisher.

Uploaded at Kaggle, a company owned by Google by [https://www.kaggle.com/arshid](https://www.kaggle.com/arshid).