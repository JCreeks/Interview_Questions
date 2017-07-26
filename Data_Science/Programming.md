```
7/26/17 First Commit
```
#### (M, R) How to compute the k-moving average of n-length time series A fast in R?

Construct a k by n matrix M where M[1,] = A[1:(n-k)], M[2,] = A[2:(n-k+1)], etc. And do 

apply(M, 1, mean)
