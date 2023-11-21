# One-Sample-T-Test
One sample T test
#Load data
library(ggplot2)
data(SamsungAdAnalysis_1_)
SamsungAdAnalysis_1_
#One Sample t-test is Greater than 55000
t.test(SamsungAdAnalysis_1_$SalesAd2, mu=55000,alternative = "greater")
