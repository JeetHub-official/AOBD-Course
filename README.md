# AOBD-Course
The repository contains various Big Data algorithms which we implemented as a part of our 'Algorithms and Optimization for Big Data' Course at School of Engineering and Applied Science, Ahmedabad University.

List:
#### 1. Simple and Multiple Linear Regression using Gradient Descent with batch data
This code consists of the implementation of simple linear regression and multiple linear regression using gradient descent on batch data. Dataset used: Sklearn boston dataset.

#### 2. Simple and Multiple Linear Regression using Gradient Descent with stream data
This code consists of the implementation of simple linear regression and multiple linear regression using gradient descent on stream data. The data is streamed using the yield function in python. Dataset used: Sklearn boston dataset.

#### 3. Simple and Multiple Linear Regression using Normal Equation Method with batch data
Normal Equation is an analytical approach to Linear Regression with a Least Square Cost Function. It is another way of doing minimization which is performed without restoring to an iterative algorithm. Dataset used: Sklearn Boston dataset

#### 4a. Incremental Mathematical Stream Regression
IMSR (Incremental Mathematical Stream Regression) is an Online Regression technique for streaming Big Data. In the context of stream data, it is required to continuously update the regression model as new data streams in, on the other hand, it is impossible to scan the entire data set multiple times due to the huge volume of the data. Hence, this technique solves this problem of traditional linear regression to update the regression model optimally and efficiently. Dataset used: Sklearn Boston dataset

#### 4b. Approimate Stream Regression 
ASR (Approximate Stream Regression) is another Online Regression technique for streaming Bug Data. This technique also solves the problem of traditional linear regression to update the regression model optimally and efficiently.Dataset used: Sklearn Boston dataset
 
#### 5. Collaborative Filtering- Stochastic Gradient Descent for Matrix Factorization
Collaborative filtering is a recommendation approach where rating of user u for item i is computed using ratings of item i given by other like minded users of u. This is an implementation of SGD for Matrix Factoriation used in Collaborative FIltering approach. This file creates a sparse random Ratings matrix whose rows are denoted by number of users and columns denote the number of items. Dataset used: Random Generation of the users items sparse matrix.

#### 6. Collaborative Filtering- Streaming Distributed Stochastic Gradient Descent for Matrix Factorization
This is an implementation of the paper [Parallel Collaborative Filtering for Streaming Data](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.230.8613&rep=rep1&type=pdf). It is a collaborative filtering approach (recommendation approach) which is done by distributing the streaming big data among different workers. This file creates a sparse random Ratings matrix whose rows are denoted by number of users and columns denote the number of items. Further, it applies collaborative filtering approach using the algorithm given in the paper by streaming the random matrix data. Dataset used: Random Generation of the users items sparse matrix.

#### 7. Stream Algorithm
The STREAM framework is based on the k-medians clustering methodology. The core idea is to break the stream into chunks, each of which is of manageable size and fits into main memory. Dataset used: Sklearn iris dataset.

#### 8. k-means and k-mediods with batch data
This code consists of the implementation of the two clustering algorithms - K-means and K-mediods. Dataset used: Sklearn iris dataset.

#### 9. CluStream Algorithm
This algorithm is an implementation of the paper [A Framework for Clustering Evolving Data Streams](http://www.vldb.org/conf/2003/papers/S04P02.pdf). This paper discusses a fundamentally different philosophy for data stream clustering which is guided by application-centered requirements. Dataset used: Sklearn digits dataset.

#### 10. ID3 with batch data
In decision tree learning, ID3 (Iterative Dichotomiser 3) is an algorithm used to generate a decision tree from a dataset. ID3 is the precursor to the C4.5 algorithm, and is typically used in the machine learning and natural language processing domains. The decision tree is formed based on splitting the nodes on attributes using Information gain to identify the relative importance of features(attributes) in the dataset. 

#### 11. CART with batch data
Classification and Regression Trees or CART for short is a term introduced by Leo Breiman to refer to Decision Tree algorithms that can be used for classification or regression predictive modeling problems. This algorithm uses Gini index to identify the relative importance of features in the dataset and thereby overcome major limitations of ID3 algorithm. 

#### 12. Hoeffding Tree Algorithm
Hoeffding Tree or VFDT is the standard decision tree algorithm for data stream classification. VFDT uses the Hoeffding bound to decide the minimum number of arriving instances to achieve certain level of confidence in splitting the node. This confidence level determines how close the statistics between the attribute chosen by VFDT and the attribute chosen by decision tree for batch learning. Dataset used: data file given in the same folder.

### Contributers:
Jeet H. Shah, 
Mihir Kanjaria, 
Muskan Matwani


