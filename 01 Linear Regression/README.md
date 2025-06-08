# What is Linear Regression?

Linear Regression is a Supervised Learning algorithm

Linear Regression predicts continuous value using a straight-line relationship between input (x) and output (y).

It fits the best line: 
    y = m x + c

## Linear Regression Algorithm Steps
Initialize weights (θ0, θ1)

Use the hypothesis 
    ℎ(𝑥)=𝜃0+𝜃1𝑥

Calculate loss using Mean Squared Error (MSE)

Update weights using Gradient Descent

Repeat until convergence

## Output
If you run this code:

* It fits a line almost exactly through the points (because y = 2x)
* You’ll see the learned slope ≈ 2 and intercept ≈ 0
* The loss curve will decrease rapidly and flatten (perfect data)
