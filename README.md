# Decision_Tree

>A decision tree is a type of machine learning model that is used for both classification and regression tasks. It is a tree-like model in which each internal node >represents a test on an attribute or feature, each branch represents the outcome of the test, and each leaf node represents a class label or a numerical value.

>In a decision tree, each node represents a feature or attribute, and each branch represents a decision or a possible outcome of that feature. The topmost node in the
>tree is called the root node, and the final outcomes are called leaf nodes. The decision tree algorithm works by recursively splitting the data into smaller subsets 
>based on the features that are most informative in predicting the target variable.

**ALGORITHM:**

> 1. Select the best feature that splits the data into the most homogeneous subsets.
> 2. Create a decision node based on that feature and connect it to the root node.
> 3. Divide the data based on the feature and create child nodes for each subset.
> 4. Repeat steps 1-3 for each child node until all the subsets are pure or a predefined stopping criteria is met.
> 5. Create leaf nodes for the final outcomes based on the majority class of the samples in that subset.
