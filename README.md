<h1 align="center">
  <br>
  <a href="https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data?resource=download"><img src="h[ttps://storage.googleapis.com/kaggle-datasets-images/721951/1255601/61caf246bebd3a50ede855b07caff2d8/dataset-cover.jpg?t=2020-06-17-07-41-37](https://preview.redd.it/6zlk0zo2f2851.gif?format=png8&s=7d60c97712d93b1ffc33a8daf2111e78ee2af06f)" alt="Country categorization" width="200"></a>
  <br>
  Country categorization
  <br>
</h1>

<h4 align="center">Unsupervised Learning K Means Model to group countries according with its data. 
</h4>

<p align="center">
  <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='scikit-learn' src='https://img.shields.io/badge/scikit-learn-100000?style=for-the-badge&logo=scikit-learn&logoColor=FFFFFF&labelColor=FF6A00&color=1882EA'/></a> <a href='https://numpy.org/' target="_blank"><img alt='numpy' src='https://img.shields.io/badge/Numpy-100000?style=for-the-badge&logo=numpy&logoColor=0250BD&labelColor=8BBFEA&color=B1DCFF'/></a>  <a href='https://pandas.pydata.org/' target="_blank"><img alt='pandas' src='https://img.shields.io/badge/pandas-100000?style=for-the-badge&logo=pandas&logoColor=2D0090&labelColor=9D7BEA&color=D2C0FA'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a> 
</p>

![screenshot](https://static.platzi.com/media/user_upload/map-e76a380a-dd9a-4551-9a16-9150238c02c0.jpg)

## Key Features

This machine learning model predicts the happines score of a given country. This prediction is a number between 0 and 10. The dataset is taken from the [World Happiness Report Kaggle Competition](https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2017.csv). So here are the key features of this project:

* Prediction is based on this country's features:
  - `country`
  - `child_mort`
  - `exports`
  - `health`
  - `imports`
  - `income`
  - `inflation`
  - `life_expec`
  - `total_fer`
  - `gdpp`
* Dimensionality reduction with **PCA**.
* Based on **Scikit-Learn** modules and functions such like:
  - `decomposition.PCA`: Dimensionality reduction.
  -  `cluster.DBSCAN` 
  -  `cluster.KMeans` 
  -  `cluster.AgglomerativeClustering` :   Hierarchical Clustering.
  - `metrics.silhouette_score` :   Main clustering score.

## How To Use

To clone and run this application, follow these steps

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/country-categorization.git

# Go into the repository
$ cd country-categorization

```

## Credits
This software uses the following open libraries and datasets:


- [Numpy](http://electron.atom.io/)
- [Matplotlib](https://nodejs.org/)
- [Seaborn](https://github.com/chjj/marked)
- [Pandas](http://showdownjs.github.io/showdown/)
- [Sci-kit Learn](http://codemirror.net/)
- [Dataset](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data?resource=download)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
