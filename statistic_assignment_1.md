# Explain the difference in the normalization constant in variance/covariance formula


The logic of doing that is to compensate our lack of information about the population data.
This correction is made to correct for the fact that these sample statistics tend to underestimate the actual parameters found in the population. they tend to contain a little bias. subtracting 1 from the sample size correct the bias.
when you work with a sample you’ve only got a small fraction of the population to work with. Therefore, your answers aren’t going to be as accurate as those you would have got, if you had the entire set of data to work with.

In the case of the sample variance the particular statistic you are working with is the sample mean (x̄) instead of the population mean(μ). Any x-value in your sample is going to be closer to x̄ than to μ.

sample calculations with n in the denominator are almost always going to be higher than calculations with n-1 in the denominator (Warne, 2017). When you subtract 1 from your sample size, it happens to turn out you’re making a fairly good adjustment for the deflated sum of squares figure as long as n isn’t huge (Edelman, 2018).


![Image result for covariance formula](https://cdn.educba.com/academy/wp-content/uploads/2019/05/Covariance-Formula.jpg)
In python the covariance matrix can be easily calculated with
## np.cov
