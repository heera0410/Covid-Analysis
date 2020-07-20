# Covid Analysis

[![OpenFaaS](https://img.shields.io/badge/Library-Matplotlib-darkblue.svg)](https://www.openfaas.com)
[![OpenFaaS](https://img.shields.io/badge/Library-Seaborn-darkgreen.svg)](https://www.openfaas.com)
[![OpenFaaS](https://img.shields.io/badge/Language-Python-purple.svg)](https://www.openfaas.com)
[![OpenFaaS](https://img.shields.io/badge/Library-Pandas-brown.svg)](https://www.openfaas.com)

-  This project is to analyse the dataset using descriptive and inferential statistics.

## Purpose of the dataset
- This dataset is taken from Kaggle which is created to provide information on covid-19.
- The dataset has 187 rows and 15 columns. 
- Features include Country/Region,Confirmed,Death,Active,Recovered,WHO Region etc.

## Descriptive Statistics 
-  A quantitative variable confirmed is taken which delivers the information of no. of confirmed cases.
-  Measure of centre and measure of variation is calculated.
-  distplot which combines hist function, kdeplot or rugplot functions is used to plot the graph
![Alt Text](https://github.com/heera0410/Covid-Analysis/blob/master/images/hist.png)
-  boxplot---> which is five no. summary of set of data such as minimum,first quartile,median,third quartile,maximum is plotted for WHO region against confirmed.
-  Pie chart and count plot is used to plot the proportion of WHO region in the dataset and to count the no. of countries in the dataset.
![Alt Text](https://github.com/heera0410/Covid-Analysis/blob/master/images/Pie.png)

## Inferential Statistics
- Sampling distribution is made on the quantitative variable confirmed.
- Central limit theorem i.e population mean is equal to sampling distribution mean is verified for variable confirmed in the dataset.
- Interval estimation of quantitative variable (Active) and qualitative variable (WHO region) is calculated using confidence interval of 90%.
- In that interval sample mean falls where population mean also resides and sample proportion for categorical variable is in the same range.
- Hypothesis testing -Two tailed test is carried on confirmed variable in csv file where null hypothesis is assumed as 10000-average of confirmed cases
which is found to be false because average is 72000 approximately hence H0 is rejected and Ha(alternative hypothesis) is accepted.
- Bootstrap distribution also known as Random Sampling with replacement- Variable considered ---> Recovered ,Sampling is made on the samples taken from the population and samples are further fetched from the previous step considered to be resamples ,process is resampling.From this the inference was population mean and bootstrap distribution mean was approximately equal.
