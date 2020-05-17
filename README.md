# UnsupervisedLearningCerialDataset
This an unsupervised data set.The data set is given below


## [Cereal Dataset Link](http://www.cs.umd.edu/hcil/hce/examples/cereal/cereal-updated.txt)

### Pre_processing
There are some missing values in the data set. There are generally two ways to deal with missing value.either delete the whole row
or replace the value with average dataset . We choose the later step for this  project. We changed the txt file to .arff file to import the data set in weka. We used the knowledge of making[ cluersing](https://www.geeksforgeeks.org/clustering-in-machine-learning/) out of these dataset. Then we choose a random cutting point from the dendogram to select the clusters. The clusters gave us different groups of clusters. 

## Outputs
* We made differnt different out of the dendogram .
* Dendogram gave us 14 clusters
* we tried to find pattern out of these clusters
* We tried to find which custer might be suited for which type of people like which clsuter of cereal should be preferd by diabetics patient, heart patient etc.
* We tried to find the correltion amongst attributes and gave comment accordingly
* brief details are in the Unsupervised report in pdf

## Used tool

* Weka - A machine leraring tool.
* CSV to arff extintion convertor.
* Excell - for finding correaltion (formula : correl(x2:x78 , y2:y78))



