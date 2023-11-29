# M1 Motorway Statistical Analysis

The analysis presented in this report seeks to validate or debunk multiple claims regarding crime in the UK made by the television documentary ‘Ross Kemp and the Armed Police’ broadcasted on the 6th of September 2018 by ITV. The documentary hypothesizes a rise in violent crimes, a preponderance of firearm incidents in Birmingham relative to other UK cities, and a close association between crimes involving firearms and drug offences.

## Description

The analysis will look at data from 2010 to 2018 and will use time series evaluation to identify violent crime trends across the UK, determining if they are increasing, decreasing, or stable. Violent crimes will fall under the crime type definition of both ‘violent crimes’ and ‘violence and sexual offences’, which will be filtered and counted from the main data frame. Several visualisation techniques will be used to clearly illustrate the behaviour of violent crime over eight years. Moreover, while not needed to prove the claim, the data will undergo several statistical steps to achieve stationarity to discuss the autocorrelation function results to better illustrate any possible patterns. A Linear regression model and a time series forecast will be created to confirm any trend seen from the visualisation methods.

A complete firearm incident analysis will follow, utilizing a combination of the two provided crime and LSOA datasets to calculate firearm incidents per head for each UK city. This will be achieved by filtering out firearm incidents (categorized as ‘possession of weapons’ and ‘offender sent to prison’) from the original data. By grouping these incidents by city, it will be possible to then calculate the rate per capita using the population density found in the Lower Layer Super Output Area (LSOA) dataset (Office for National Statistics, n.d.).The provided conclusion, together with compelling visual plots and statistical analysis (including percentile rank and Z-score), will demonstrate whether the claims made by the documentary in 2018 were greatly exaggerated or whether they reflected the truth.

Finally, to elucidate any potential correlation between firearm incidents and drug offences, this analysis will look at firearm crimes and drug crimes by isolating them and counting them from the original data set. By aggregating these two variables it will be possible to use Pearson and Spearman’s correlation coefficients (and scatter plots with regression lines) to determine the strength of any association between firearm crimes and drug crimes. This report will examine both a temporal approach and a spatial approach to determine if drug and firearm crimes are correlated through time and geographical location. The final objective is to weave a coherent tapestry of crime dynamics in the UK, grounded in empirical evidence, and to assess the claims made in 2018 by the television documentary “Ross Kemp and the Armed Police”.

## Getting Started

### Dependencies

Before installing and running this project, please ensure you meet the following requirements:

Operating System:

Windows: Windows 10 or later is recommended for optimal compatibility.
macOS: A recent version (macOS Catalina or later) is advisable.
Linux: Any modern distribution (like Ubuntu 20.04 LTS or later) should work well.
Programming Environment:

This project was created using Jupyter Notebook and the latest Python/PySpark release.

## Authors

Yuri Lazzeretti

ylazz001@gmail.com

www.linkedin.com/in/yuri-lazzeretti-b63a22220

## License

This project is licensed under the GNU License - see the LICENSE.md file for details
