# predication-using-DecissionTree-algorithm
predication using DecissionTree algorithm for iris dataset and visualization the decission tree
A Decision Tree is a supervised algorithm used in machine learning. It is using a binary tree graph (each node has two children) to assign for each data sample a target value. The target values are presented in the tree leaves. To reach to the leaf, the sample is propagated through nodes, starting at the root node. In each node a decision is made, to which descendant node it should go. A decision is made based on the selected sample’s feature. Decision Tree learning is a process of finding the optimal rules in each internal tree node according to the selected metric.

# 1: The decision trees can be divided, with respect to the target values, into:
**Classification trees used to classify samples, assign to a limited set of values - classes. In scikit-learn it is DecisionTreeClassifier.**
**Regression trees used to assign samples into numerical values within the range. In scikit-learn it is DecisionTreeRegressor.**

# Decision trees are a popular tool in decision analysis. They can support decisions thanks to the visual representation of each decision.

** Here i use plot with sklearn.tree.plot_tree method (matplotlib needed) to visualize it**

# 2: Train Decision Tree on Classification Task
I will train a DecisionTreeClassifier on iris dataset. I will use default hyper-parameters for the classifier.

# 3: Plot Tree with plot_tree
The plot_tree method was added to sklearn in version 0.21. It requires matplotlib to be installed. It allows us to easily produce figure of the tree (without intermediate exporting to graphviz) 
