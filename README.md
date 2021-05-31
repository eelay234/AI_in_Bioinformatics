# AI in Bioinformatics
This project explores how machine learning, deep neural network, and natural language processing techniques can be applied to Boinformatics in the areas of gene/protein expression, sequence analysis, strucural bioinformatics, network and system biology[1].

The main steps are as follows:
First, data are collected and converted to the format if necessary that can be used by the programs, for example, .arff to .csv file.
Next, data are pre-processed to drop nan values, remove columns that are not relevant, convert categories into numeric values.
After that, split the data into training data and testing data if they are not seperated yet. Then scale the values to be within comparable range.
Reduce the number of features if it is huge.
Perform hyperparameters to pick the best hyperparameters.
Train the model by using the best parameters.
Do prediction and evaluate the performance.

References:
1. "Artificial Intelligence in Bioinformatics" course at edx.org
2. The code of scaling values and selecting the best parameters follows https://www.kdnuggets.com/2019/09/explore-world-bioinformatics-machine-learning.html
3. The code of using SGD for optimization, measuring running time, and searching for the best number of iteration follows https://michael-fuchs-python.netlify.app/2019/11/11/introduction-to-sgd-classifier/
