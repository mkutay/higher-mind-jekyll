# Linear Regression

Created: January 24, 2022 11:01 AM

## Linear Regression Model

$h_\theta(x)=\theta_0 + \theta_1x$

$J(\theta_0, \theta_1)=\frac{1}{2m} \displaystyle\sum_{i=1} ^{m}(h_\theta(x^{(i)}) - y^{(i)})^2$

## Gradient Descent

if you start 5 steps right it can go to a different place

repear until convergence

$\theta_j := \theta_j - \alpha \frac{\partial}{\partial\theta_j}J(\theta_0, \theta_1)$ (simultaneously update j = 0 and j = 1)

$\alpha$: learning rate, second term: derivative term

- if $\alpha$ is too small, gradient descent can be slow
- otherwise if $\alpha$ is too big, gradient descent can overshoot the minimum. It may fail to converge or even diverge.
- what happens when $\theta_1$is at the local minimum
    
    slope (derivative) will be 0 therefore, $\theta_1$won’t change
    

gradient descent can converge to a local minimum, even when $\alpha$ is fixed

As we approach to local minimum, gradient descent will automatically take smaller steps. Therefore, there is no need to decrease $\alpha$ over time.

“Convex Function”

“Batch” gradient descent

multivariate linear regression

repeat

$\theta_j:=\theta_j-\alpha\frac{1}{m}\displaystyle\sum_{i=1} ^{m}(h_\theta(x^{(i)})-y^{(i)})x_j^{(i)}$

simultaneously update $\theta_j$for $j=0, ..., n$