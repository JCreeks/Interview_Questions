```
7/26/17 First Commit
```
#### (Regularization) What is the difference between Ridge and Lasso regression?

#### (SVM) Can you use Support Vector Machine to do multi-class classification?

LibSVM uses the *one-against-one* approach for multi-class learning problems. From the [FAQ][1]:

> Q: What method does libsvm use for multi-class SVM ? Why don't you use the "1-against-the rest" method ? 
>
>It is one-against-one. We chose it after doing the following comparison: C.-W. Hsu and C.-J. Lin. [A comparison of methods for multi-class support vector machines][2], IEEE Transactions on Neural Networks, 13(2002), 415-425.
>
> "1-against-the rest" is a good method whose performance is comparable to "1-against-1." We do the latter simply because its training time is shorter.

[1]: http://www.csie.ntu.edu.tw/~cjlin/libsvm/faq.html#f419
[2]: http://www.csie.ntu.edu.tw/~cjlin/papers/multisvm.pdf

#### (Overfitting) What methods can be used to prevent overfitting?

> simpler model structure

> regularization

> data augemntation

> dropout

> Boostrap/Bagging

> ensemble

> early stopping

> Bayesian

#### (Naive Bayes) What are the disadvantages of using a naive bayes for classification?
