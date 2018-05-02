# 142

1. iid assumption: independent and identically distributed(iid): A collection of random variables is iid if they all have the same probability distribution, and all are mutually independent. 


2. supervised learning： classification:labels are nominal

- Binary Classification:{spam,not-spam}
- Multi-class classification:{0,1,2,3},{positive,negative,neutral}
- regression:labes are numeric(e.g. price of house)
- ranking problems(order a set of objects)
- reinforcement learning: 
- output:sequence of actions. Individual actions arenot correct/incorrect but the overall policy is important
- no supervised output, but delayed reward
- On-line learning:train on one instance at a time: perceptron , contrasted with batch learning.
- Active learning- request labels for particular instances.
3. Unspervied learning- no labels provided at all at train time
- clustering 
- image compression, bioinformatics.
4. Semi-supervised learning-used labeled as well as unlabeled data
5.  Choosing a hypothesis too simple, fewer parameters to learn, but less powerful.

- Model has less variance:fewer changes with changing training data, model has more bias makes more assumptions. 
6. Choosing a hypothesis too complex, more parameters to learn but more powerful, more variance and less bias. Called bias-variance tradeoff.
7. Bias represents estimation error(limitation of the model)
Variance represent approximation error(limitations of the model family)
8. error(g)=bias+variacne. 
9. over-fitting results in models that are more complex than necessary:after learning knowledge they "tend to learn noise". More complex models tend to have more complicated decision boundaries and tend to be more sensitive to noise, and missing examples.
10. Underfitting does not represents data well enough.

11. various evalutation measures exist in literature that can evaluate predictive performance.
Most popular for classification:accuracy and error rate, precision recall and F-measure.

accuracy = $\frac { correct predictions }{number of test instances}$


error = 1 - accuracy

confustion matrix https://ucsc-courses.github.io/CMPS142-Spring2018/slides/Lecture1_2.pdf P35

12. k-fold	cross	validation	
13. Discriminative learning:model the problem of text correction as a problem of learning from examples. Goal:learn directly how to make predictions. Model the problem of text correction as a problem of learning from examples. Goal: learn directly how to make predictions