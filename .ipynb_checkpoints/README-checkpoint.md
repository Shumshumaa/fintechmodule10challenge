Crypto Portfolio Analyzer


This file clusters cryptocurrencies by their performance in different time periods. We've then plot the results so we can visually show the performance of the analysis to the board of our investment firm.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For data manipulation and analysis.
* [hvplot](https://hvplot.holoviz.org/) - For interactive user prompts and dialogs
* [pathlib](https://docs.python.org/3/library/pathlib.html) - To provide for an easier method to interact with the filesystem no matter what the operating system is.
* [sci-kitlearn](https://scikit-learn.org/stable/) -  A simple tool used for predictive data analysis



---

## Installation Guide

Before running the application first install the following dependencies.

``` pyviz
  conda install -c pyviz hvplot geoviews
```

``` sci-kitlearn
    pip install -U scikit-learn
```
---

## 

In order to run this analysis, we use various tools from the sci-kitlearn library: "Kmeans", "PCA" and "StandardScaler". Please use the following libraries from sci-kitlearn to operate this notebook:

    from sklearn.cluster import KMeans
    from sklearn.decomposition import PCA
    from sklearn.preprocessing import StandardScaler

---

## Contributors

Brought to you by PShum FinTech Consulting

---

## License

MIT
© 2007 - 2023, scikit-learn developers (BSD License)