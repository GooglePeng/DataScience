Data Science Terminologies
==========

## Feature Extraction

**Term Frequency (TF)**

**Term Frequency-Inverse Document Frequency (TF-IDF)**

**Mutual Information Weight of a Term in a Document** $$w_{ij} = \log_2 \left(\frac{TF_{ij}/S}{\sum_{i'=1}^N TF_{i'j}/S \sum_{j'=1}^NTF_{ij'}/S} + 1\right)$$


## Similarity and Dissimilarity Measures

**Euclidean distance**

**Cosine similarity**


**KL-divergence**


**0-1 Loss** 
```tex 
l_{0-1}=\left\{ \begin{array}{ll} 0 & if h(X)=y\\ 1 & if h(x)\ne y\end{array} \right.
```

**Square Loss**

**Low-pass filter** dealing with noise in time-series data (signals)

**Geometric Mean**

**Trimean (TM)**

**Interquartile Mean (IQM)**


**Fisher transformation**


**Platt Scaling**


**Jacknifing**


**Fisher Transformation**

**Point Biserial**

**ANOVA (Analysis of Variance)

**Weighted Least-Square Regression**

**RANSAC (Random Sample Consensus)** 



**Conditional Random Field**



## Probability Theory

**Joint probability** $p(x,y)$

**Conditional probability** $p(y|x)$

**Muttual Informaiton (MI)** $MI(x,y) = \frac{p(x,y)}{p(x)p(y)}$

**Conditional Mutual Information** $MI(A;B|C) = MI(A;B,C) - MI(A;C)$


### Sampling

**Jackknife resampling** is a technique that predates *bootstrap* sampling technique for estimateing the precision of sample statistics (mean, median, ..). Given a dataset of size $N$, Jackknife resampling uses the leave-one-out technique to calculate the desired parameter using the remaining $N-1$.This process is repated for each saple point, and finally the aggregate of all the estimates is the Jackknife estimator of that parameter. (The main difference with bootstrap is that in bootstrap technique, subsets are drawn randomly with replacement.)


## Evaluation Metrics

**Cohens kappa coefficient**

### Clustering

**Purity**

**Mutual Information**

**Rand Index**
