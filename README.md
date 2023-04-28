# Decision_Tree

>A decision tree is a type of machine learning model that is used for both classification and regression tasks. It is a tree-like model in which each internal node >represents a test on an attribute or feature, each branch represents the outcome of the test, and each leaf node represents a class label or a numerical value.

>In a decision tree, each node represents a feature or attribute, and each branch represents a decision or a possible outcome of that feature. The topmost node in the
>tree is called the root node, and the final outcomes are called leaf nodes. The decision tree algorithm works by recursively splitting the data into smaller subsets 
>based on the features that are most informative in predicting the target variable.

**How to search a good ***decision tree***?**

>The space of decision trees is too big for systematic search.
>>* Stop and
>>-return the value of a target feature.
>>-or a distribution over the target feature values.
>* Choose a test(eg. an input feature) to split on.
>>- For each value of the test, build a subtree for those examples with this value of test.

**ALGORITHM:**

> 1. Select the best feature that splits the data into the most homogeneous subsets.
> 2. Create a decision node based on that feature and connect it to the root node.
> 3. Divide the data based on the feature and create child nodes for each subset.
> 4. Repeat steps 1-3 for each child node until all the subsets are pure or a predefined stopping criteria is met.
> 5. Create leaf nodes for the final outcomes based on the majority class of the samples in that subset.

**EXAMPLE:**

>Below is the diagram for decision tree
>![Decision_tree1](https://user-images.githubusercontent.com/107355282/234040111-e70d5e19-3cc4-4216-9431-5e54834daac3.png)
>
>> In the decision tree diagram,a person has to take a decision whether he should go for a run or not? This is the root node.
>> 
>>In the next level of tree he has to take to decision whether yes or no.
>>
>>If yes,then the machine will ask for weather condition,i.e, is it raining or sunny? If it is raining then stay or go and if it is sunny then he has to go.
>>
>>If no,then he might be busy and he has to stay.This is the leaf node.

**ADVANTAGES**

>1. **Easy to understand and interpret**: Decision trees are easy to understand and interpret, even for non-technical users. They can be visualized easily, allowing >users to quickly grasp the underlying logic.
>
>2. **Able to handle both categorical and numerical data**: Decision trees can handle both categorical and numerical data, making them a versatile algorithm for a wide range >of applications.
>
>3. **Can handle missing values**: Decision trees can handle missing values by using surrogate splits to replace the missing values with the next best variable.
>
>4. **Can handle non-linear relationships**: Decision trees can handle non-linear relationships between variables, making them a good choice for data that doesn't follow a >linear pattern.
>
>5. **Can be used for feature selection**: Decision trees can be used for feature selection by identifying the most important variables that contribute to the target >variable.
>
>6. **Can be combined with other algorithms**: Decision trees can be combined with other algorithms, such as ensemble methods like random forests or boosting, to >improve their performance.
>
>7. **Efficient for large datasets**: Decision trees can be efficient for large datasets, as they can quickly narrow down the number of variables that are relevant to >the target variable.

**DISADVANTAGES**

>1.**Overfitting**: Decision trees are prone to overfitting, meaning they may create a complex model that fits the training data too well, but does not generalize well >to new data.
>
>2. **Instability**: Decision trees can be sensitive to small variations in the data, which can cause instability in the model.
>
>3. **Bias**: Decision trees can be biased towards features with more levels, leading to an uneven representation of the data.
>
>4. **Difficulty with continuous variables**: Decision trees can have difficulty with continuous variables, as they may require many splits to capture the full range >of values, which can result in overfitting.
>
>5. **Difficulty with class imbalance**: Decision trees can struggle with class imbalance, where one class is significantly more prevalent than the other, as the >algorithm may prioritize the majority class.
>
>6. **Lack of robustness**: Decision trees can be sensitive to changes in the data, such as outliers or missing values, which can result in changes to the final model.
>
>7. **Greedy nature**: Decision trees are a greedy algorithm, meaning they make the best decision at each step without considering future steps, which can result in >suboptimal solutions.

>***This Algorithm might tend to fall in overfitting***












