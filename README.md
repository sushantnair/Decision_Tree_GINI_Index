# Decision_Tree_GINI_Index
A Python implementation of the Decision Tree Algorithm

## Purpose
This code is meant to foster an in-depth understanding of the Decision Tree Algorithm used in Machine Learning.

## Implementation Details
This code has been written purely in Python to implement the ID3 Decision Tree Algorithm used in Machine Learning.

### Libraries Used
Pandas for dataframe manipulation <br>
Networkx for visualization of the Decision Tree <br>
Combinations (in Itertools library) to generate combinations of values of variable (column) <br>
Matplotlib for plotting graphs <br>
Math for mathematical operations like squaring and logarithms.

### Special Note
No ML algorithms like Scikit-learn, PyTorch or TensorFlow has been used. This is intentional,
so that every step of the process is coded for better understanding of the algorithm.

## Methodology
I have added the Colab notebook for the code. I have deliberately done this, so that every step of the code can be run
to promote an in-depth understanding of the algorithm.

## Dataset and Py Code
Click on the link: https://github.com/sushantnair/ML/tree/main/experiment_4
Use the BuyCarNew.csv dataset for best results.

## Issues
There are currently **three** issues, which I'd like the learner to solve for better understanding
of the algorithm by practical experience. The issues can be found in the issues section. Plus,
**ensure that you don't use ML libraries, or change the code so much that it loses its identity**.
I have deliberately not used ML libraries so that each step of the process can be exposed to enable
better understanding for learners.

## About GINI Index
The latter part of the code is the implementation of GINI Index in order to choose the appropriate 
partitioning of the dataset. Earlier in the code, the rootnode for a dataset is found based on 
Gain in Information and the dataset is partitioned based simply on the values of the rootnode column. 
For a dataset, the node which gives maximum Information Gain is chosen as the rootnode and the dataset 
is partitioned accordingly. However, there is a precise method in order to determine the dataset partitions 
and that is GINI Index. It helps in determining the correct partitions. For example, for the BuyCarNew.csv 
dataset the rootnode is Age. Now Age has three values Young, Middleage and Senior, so the partition 
(as can be seen in the tree) has been done such that one brance is for Age Young, the middle branch is for 
Age Middleage and the third branch is for Age Senior. So this may not be the best way to partition the dataset. 
This is where GINI Index can be used to create better partitions. However, I am only doing concept implementation 
here, so I have decided to keep the two parts (main Decision Tree part and GINI Index part) seperate. 
Of course, you may go ahead and merge the two, but please don't submit a PR to modify the existing 
decisiontree_gini.py code. However you surely can submit a PR to add the merged code as new code to this repository.

## Documentation
Coming soon...

## Licensing
GNU General Public Licence. You may use the code for free, no attribution required (although it'd be
appreciated!).

Thank you very much. Please consider starring the repository if it has helped or delighted you.

