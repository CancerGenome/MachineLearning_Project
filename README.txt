### Projects for Machine Learning 

## Before running----
# Package requirement
#
Decision Tree: Rpart;
Neural Network (NN): neuralnet
Boosting: gbm
Support Vector Machine(SVM): e1071
k-Nearest Neighbors (KNN): class

## Start to Run ------
##Scripts: (Rscript *.R )
Decision_Tree.R: for decision tree
Boost.R: for boosting method
KNN.R: for k nearest method
NN.R: for neural network
SVM.R: for SVM 

# Data
test.csv:  testing data, about 25% of origianl train data
train.csv: training data, about 75% of original train data
Original_train.csv: this is the original file of trainning data. I split a certain proportion of this as the train data (train.csv), while keep others as test (test.csv)

## Function
format_output.R: R function for format the output
process_input.R: R function for prepare the input

#### Attention: 
I am using test.csv and train.csv in this directory as my default input. 
In my report, I also compared the effect of different sample size. If you want
to run that  analysis, you should replace files in following directory with
file in current direcotry
## data66
test.csv:  testing data, about 33% of origianl train data
train.csv: training data, about 66% of original train data
## data50
test.csv:  testing data, about 50% of origianl train data
train.csv: training data, about 50% of original train data
