# ML_Algos

## 07.K-Means Clustering
 
 __K-means clustering__ is a type of __unsupervised learning__, which is used when you have __unlabeled data (i.e., data without defined categories or groups)__. 
> __The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K__. <br>

- The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. <br>
- Data points are clustered based on feature similarity.<br>

The results of the __K-means clustering algorithm__ are:
1. The centroids of the K clusters, which can be used to label new data
2. Labels for the training data (each data point is assigned to a single cluster)
![image.png](https://cdn-images-1.medium.com/max/716/1*WkU1q0Cuha2QKU5JnkcZBw.gif)

## 08.KNN
__KNN__ can be used for both __classification and regression__ predictive problems. However, it is more widely used in classification problems in the industry

### 08.1 KNN for Regression
When KNN is used for regression problems the _prediction is based on the __mean or the median__ of the K-most similar instances_.<img src="https://raw.githubusercontent.com/insaid2018/Term-3/master/Images/download%20(2).png" />

### 08.2 KNN for Classification
When KNN is used for classification, the output can be calculated as the __class with the highest frequency__ from the __K-most similar instances__. Each instance in essence __votes for their class and the class with the most votes is taken as the prediction__.

Class probabilities can be calculated as the normalized frequency of samples that belong to each class in the set of K most similar instances for a new data instance. For example, in a binary classification problem (class is 0 or 1):

p(class=0) = count(class=0) / (count(class=0)+count(class=1))

If you are using K and you have an even number of classes (e.g. 2) it is a good idea to choose a K value with an odd number to avoid a tie. And the inverse, use an even number for K when you have an odd number of classes.
<img src="https://raw.githubusercontent.com/insaid2018/Term-3/master/Images/download%20(3).png" />

## 09.Naive Bayes Classifier

- Collection of __classification__ algorithms based on __Bayes Theorem__.
- Classifies given different __instances (object/data)__ into __predefined classes(groups)__, assuming there is no interdependency of features __(class conditional independence)__.
<img src="https://raw.githubusercontent.com/insaid2018/Term-3/master/Images/21.png" width="700" height="600" />
<img src="https://raw.githubusercontent.com/insaid2018/Term-3/master/Images/22.png" width="700" height="600" />

## 10.PCA-Dimensionality reduction
PCA is a method used for compressing a lot of data into something that captures the essence of the original data.
- It reduces the dimension of your data with the aim of retaining as much information as possible.
- Calculated efficiently with computer programs
- This method combines highly correlated variables together to form a smaller number of an artificial set of variables.
- These artificial set of variables are called 'principal components' that account for most variance in the data.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=BfTMmoDFXyE
" target="_blank"><img src="http://img.youtube.com/vi/BfTMmoDFXyE/0.jpg" 
alt="A layman's introduction to principal component analysis" width="240" height="180" border="10" /></a>

![image.png](https://raw.githubusercontent.com/insaid2018/Term-3/master/Images/Q7HIP.gif)