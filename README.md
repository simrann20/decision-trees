## Decision Trees Implementation on Iris Dataset


The implementation of decision trees from scratch on the iris dataset is available in this repository. The decision tree algorithm is created without relying on pre-existing libraries or frameworks. The iris dataset, a widely used benchmark dataset, is utilized for this implementation.

#### About the algorithm

The decision tree algorithm starts by analyzing the iris dataset, which consists of various features such as sepal length, sepal width, petal length, and petal width, along with corresponding labels representing different species of iris flowers. The goal is to build a decision tree model that can accurately classify iris flowers based on these features.

The repository provides code and documentation that demonstrates the step-by-step process of building a decision tree. This involves selecting the best feature to split the dataset at each node based on certain criteria, such as information gain or Gini impurity. The algorithm recursively constructs the tree by creating child nodes and further splitting the data based on different features until a stopping criterion is met, such as reaching a maximum depth or minimum number of samples.

Once the decision tree is constructed, the repository includes methods to predict the species of iris flowers for new, unseen instances based on their feature values. This is achieved by traversing the decision tree and following the appropriate path based on the feature values of the instance.

The implementation also includes functionalities for evaluating the performance of the decision tree model, such as calculating accuracy, precision, recall, and F1-score. These metrics help assess the effectiveness of the decision tree in correctly classifying iris flowers.

Overall, this repository provides a detailed and self-contained implementation of decision trees from scratch on the iris dataset. It allows users to understand the inner workings of the decision tree algorithm and apply it to other datasets or modify it according to their requirements.
