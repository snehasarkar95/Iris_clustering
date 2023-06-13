# Iris_clustering
 
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.

It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

The columns in this dataset are:

1. Id
2. SepalLengthCm
3. SepalWidthCm
4. PetalLengthCm
5. PetalWidthCm
6. Species


# Observations

* data set contains 150 entries
* data set contains no null values
* Highest frequency of sepal length is b/w 30 and 35 which is b/w 5.5 & 6
* Highest frequency of sepal width is around 70 which is b/w 3.0 & 3.5
* Highest frequency of petal length is around 50 which is b/w 1 & 2
* Highest frequency of petal width is around 50 which is b/w 0.0 & 0.5
* Data variables are not normally distributed
* For Sepal Length, Sepal Width, Petal Length, Petal Width shows major overlapping for Iris-versicolor, Iris-virginica.
* Iris-setosa has most definite speration from the other two categories except for Sepal Width.
* Thus can conclude that sepal width would be the most prominent feature for clustering.

* Clustered the data using K-Means as the data is small.
* Using Elbow method and silhouette score net clusters are 3

