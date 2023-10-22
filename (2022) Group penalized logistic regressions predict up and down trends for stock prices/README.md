[*Group penalized logistic regressions predict up and down trends for stock prices North American Journal of Economics and Finance 59 (2022) 101564*](https://www.sciencedirect.com/science/article/abs/pii/S1062940821001716?via%3Dihub)

**Summary:**

* In the Jupyter notebook I investigate Amazon dataset which the reported test set accuracy is listed as `0.7330`, but I am unable to determine the source of this high accuracy due to the limited information provided. In my replication, I achieved a more realistic accuracy of `0.5495`.
* I have contacted the authors of the study after completing my Jupyter notebook and uploading it to GitHub in order to request more information about their approach.

**Background:**

* In order to improve the prediction accuracy and bring huge economic benefit for investors, the authors proposed group SCAD/MCP penalized logistic regressions to predict up and down trends for stock prices for the different data sets from BAC, Amazon, and Citibank.
* Authors selected 24 technical indicators through common sense and trial and error, and according to their essential attributes, divide them into the five groups: moving average indicators, oscillator indicators, trend indicators, volume indicators and volatility indicators.
* By group screening, they found that the `oscillator indicator group` (containing 6 indicators) is a critical technical indicator group that affects the stock trend.
* For the three data sets, their prediction accuracies all exceed 71%, and their AUC values all exceed 0.78. 
* In my opinion the results are remarkably high and alarmed me immedietaly so I decided to investigate it further.