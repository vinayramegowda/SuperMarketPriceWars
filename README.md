# SuperMarketPriceWars
Compare prices of supermarkets and find out which ones cheaper

The aim of this investigation is to compare the prices of two of the well-known supermarkets and draw conclusions as to which supermarket is cheaper than the other. The data collected was compiled directly from their website and manually from their stores. Sixty-five different products were randomly observed in total and we made sure to select only those products which are available in both the stores. The prepared data is then imported into Rstudio.

To describe the data, we obtained summary statistics of the entire data and for better visualization we plotted a boxplot for each supermarket. A paired t-test is run on the dataset to figure which of the two retailers have the cheaper prices. To run paired t-test we must ensure the data collected has equal variance and is normal. Since our data set has more than 30 records it is considered as normal according to Central Limit Theorem. Then a Levene test with a significance level of 0.05 is run to check the homogeneity of variances among the two retailers. Firstly, we perform Fisher test to check whether there is any homogeneity in the data.

Later on, if we perform t-test ,the p-value of the dataset is analysed with the significance level of 0.05. After performing the paired t-test on the data we get p-value as 0.01665 which is less than the significance value of 0.05 and hence is statistically significant. 
