# Gradient Descent Variants

In this notebook, we explore three variants of the gradient descent algorithm, each with its unique approach to updating model parameters:

1. **Batch Gradient Descent**:
   - Utilizes the entire dataset to update parameters (Theta0 and Theta1) in a single iteration.
   - Robust but computationally expensive, especially for large datasets.

2. **Stochastic Gradient Descent (SGD)**:
   - Processes one training example at a time to update parameters incrementally.
   - Faster and less memory-intensive than batch gradient descent, suitable for online learning scenarios.

3. **Mini-Batch Gradient Descent**:
   - Divides the dataset into small batches and updates parameters based on each batch.
   - Strikes a balance between the efficiency of batch gradient descent and the quick adaptability of stochastic gradient descent.

## Key Concepts Explored:

- **Hypothesis Function**: The fundamental function capturing the relationship between features and output.
- **Cost Function**: Evaluation metric for the accuracy of the model's predictions.
- **Parameter Updates**: The process of adjusting Theta0 and Theta1 to minimize the cost function.
- **Learning Rate**: The step size in each iteration, influencing the convergence speed and stability.

By examining these gradient descent variants, we gain insights into their strengths, weaknesses, and areas of application. Understanding the nuances of each variant is crucial for selecting the most suitable approach based on dataset size, computational resources, and the dynamics of the optimization problem.
