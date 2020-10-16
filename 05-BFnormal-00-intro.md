# Hypothesis Testing with Normal Populations

In Section \@ref(sec:bayes-factors), we described how the Bayes factors can be used for hypothesis testing. Now we will use the Bayes factors to compare normal means, i.e., test whether the mean of a population is zero or compare two groups of normally-distributed populations. We divide this mission into three cases: known variance for a single population, unknown variance for a single population using paired data, and unknown variance using two independent groups.

Also note that some of the examples in this section use an experimental update to the `bayes_inference` function that are not provided in the CRAN released version of the package. To get the experimental version you can install the `BayesFactor` branch from GitHub using the following command in R,

```r
remotes::install_github("statswithr/statsr@BayesFactor")
```
If your local output differents from what is seen in this chapter, or the provided code fails to run for you this is the most likely cause.



