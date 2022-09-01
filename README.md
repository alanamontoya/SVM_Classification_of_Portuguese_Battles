# SVM_Classification_of_Portuguese_Battles

Summary:

*	Predicted the outcome of Portuguese battles from the number of Portuguese, Dutch, and English ships involved as well as Spanish involvement.
*	Fit a SVM classifier in Python using 5-fold stratified cross-validation to predict whether a Portuguese battle resulted in a win, loss, or draw.
*	Concluded that the model produced low average accuracies (roughly 40%) due to the small size of the dataset and imbalanced classes. It was determined that significantly more data would be needed.

Files:

* _SVM_Classification_of_Portuguese_Battles.ipynb_: 
    * Contains the process of analyzing the data, developing SVM models, and assessing the results. These results were then compared to the performance of decision tree and Naive Bayes models. 
* _armada.xls_:
    * Data on Portuguese sea battles that contains outcomes of naval battles between Portuguese and Dutch/British ships between 1583 and 1663. The data was obtained from here: http://users.stat.ufl.edu/~winner/data/armada.dat.
