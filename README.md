# Statistics_learning
Statistical methods
## Bootstrapping
It is a statistical procedure that resamples a single dataset to create many simulated samples, which allows you to calculate the standard errors, construct confidence intervals, and perform hypothesis testing for numerous types of sample statistics.

Traditionally, we want to calcualte the mean, std, or meadian, etc. based on the sampling distribution, but we nned proper test statistic and satisfy the assumptions. By contrast, the bootstrap method resample the sample data over and over to create many simulated samples. Each of these samples has its own properties, like the mean, median, std, etc. So we can observe its distribution by showing these means on a histogram. We do not need to worry about test statistics, formulas, or assumptions. The bootstrap procedure uses these sampling distributions as the foundation for confidence intervals and hypothesis testing.

The central assumption for bootstrapping is that the original sample accurately represents the actual population.
