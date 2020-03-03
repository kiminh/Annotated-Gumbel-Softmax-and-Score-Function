# The Annotated Gumbel Softmax and Score Function Estimator: An Engineering Perspective

Yao Fu, Columbia University 

yao.fu@columbia.edu

The gumbel-softmax and the score function estimator are the two most widely used estimators for back-propagating gradients through non-differentiable variables.
In NLP this typically means discrete structures, typically categorical variables, linear chains, trees .etc. 
with the parameterization by HMMs, CRFs and neural networks. 
To show the implementation details, to study the basic behaviors of the two estimators from an engineering perspective, to give people what to expect, and to show the best practice, we present the annotated notebooks for them. 

Citation:

```
@article{yao2020annotated_gumbel_score,
  title   = "The Annotated Gumbel Softmax and Score Function Estimator",
  author  = "Yao Fu",
  year    = "2020",
  url     = "https://github.com/FranxYao/Annotated-Gumbel-Softmax-and-Score-Function"
}
```

