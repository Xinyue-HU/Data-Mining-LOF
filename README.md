# Local Outlier Factor (LOF) for Outlier Detection

The mini project focus on the Outlier Detection task which is one of the most important topics in fundamental data mining. 
I use LOF (local outlier factor, in density- based model) as a key indicator to analysis the real-world data sets.
I found the two awesome data sets, both from "Unsupervised Anomaly Detection Dataverse" at Harvard (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OPQMVF).

Data set 1 (pen-global-unsupervised): The whole data set contains pen-local-unsupervised and pen-global-unsupervised, and pen-local-unsupervised is not included in this project. 
I intended to find a relatively small dataset at first: there are in total 16 attributes and 800+ rows in pen-global-unsupervised. 
All input attributes are integers ranging from 0 to 100. The meaning of each attribute could be somewhat ambiguous because they did some pre-processing on the coordinate information and represented digits as constant length feature vectors. 
Although the algorithm can handle 16 attributes, it takes longer time to run the program and hard to do visualization, so I decided to just choose the 3 dimensions among 16 as data pre-processing. 
I tried different combinations and use the one that seems would spot obvious outliers.

Data set 2 (Shuttle): The shuttle dataset contains 9 attributes all of which are numerical and there are in total 46000+ rows which is a large dataset. 
Very cool part of this data set is that it is provided by NASA. Consider the huge size of the dataset, finding all the outliers takes huge amount of time, but what we can do instead is individual query.
