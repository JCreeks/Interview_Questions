```
7/26/17 First Commit
```
#### (Mis) What is different between Random Forests and Gradient Boosted Trees?

From [1]:
> Algorithmic difference is; Random Forests are trained with random sample of data (even more randomized cases available like feature randomization) and it trusts randomization to have better generalization performance on out of train set.
On the other spectrum, Gradient Boosted Trees algorithm additionally tries to find optimal linear combination of trees (assume final model is the weighted sum of predictions of individual trees) in relation to given train data. This extra tuning might be deemed as the difference. Note that, there are many variations of those algorithms as well.
>
> At the practical side; owing to this tuning stage, Gradient Boosted Trees are more susceptible to jiggling data. This final stage makes GBT more likely to overfit therefore if the test cases are inclined to be so verbose compared to train cases this algorithm starts lacking. On the contrary, Random Forests are better to strain on overfitting although it is lacking on the other way around.
So the best choice depends to the case your have as always.
[1]: http://www.erogol.com/different-random-forests-gradient-boosted-trees/

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

#### (Regularization) What is the difference between Ridge and Lasso regression?
