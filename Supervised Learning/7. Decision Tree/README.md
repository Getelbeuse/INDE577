## Introduction to Decision Trees

Decision Trees are a popular and powerful type of machine learning algorithm that are used for both classification and regression tasks. They mimic human decision-making processes by creating a model that predicts the value of a target variable based on several input variables.

A Decision Tree splits the data into branches, which represent a decision path about the data points. The topmost decision node in a tree corresponds to the best predictor called the root node. Decision Trees split the dataset into distinct nodes, where one node corresponds to one attribute.

### Key Concepts

- **Node**: Test for the value of a certain attribute.
- **Edge/Branch**: Outcome of a test and leads to the next node or leaf.
- **Leaf nodes**: Terminal nodes that predict the outcome (represent class labels or regression values).

### Building a Decision Tree

1. **Select the Best Attribute**: Use statistical measures, such as information gain or Gini impurity, to select the attribute that best separates the samples into distinct classes.
2. **Branch on the Chosen Attribute**: Split the dataset into subsets that contain possible values for the chosen attribute. Perform this recursively on each derived subset.
3. **Recursion Termination**: The recursion is terminated when one of the conditions is met:
   - All elements in the subset belong to the same class.
   - There are no more remaining attributes.
   - There is no more data to split.

### Applications

Decision Trees are used in various applications including:
- **Credit Scoring**
- **Medical Diagnosis**
- **Stock Trading Decisions**
- **Customer Segmentation**

### Advantages and Disadvantages

- **Advantages**:
  - Easy to understand and interpret.
  - Requires little data preparation.
  - Can handle both numerical and categorical data.
  
- **Disadvantages**:
  - Prone to overfitting, especially with complex trees.
  - Can become unstable because small variations in data might result in a completely different tree being generated.
  - Decision boundary limitations since they are all orthogonal to the axis.