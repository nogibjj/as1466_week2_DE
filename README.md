# IDS706-Week1-project

[![Python CI](https://github.com/Nastiiasaenko/IDS706-Week1-project/actions/workflows/main.yml/badge.svg)](https://github.com/Nastiiasaenko/IDS706-Week1-project/actions/workflows/main.yml) 

This is a week-1 assigment project for IDS706 by Anastasiia Saenko (as1466 Duke NetId).
This is a template for Python projects, and it includes: 

* Devcontainer with DockerFile
* workflows with github actions
* gitingnore file
* this Readme.md file
* requirements.txt file
* main.py file testing a simple sum function and test cases for this function in tests folder

# This is the generated report for summary statistics and data visualization for [bmi.csv](https://github.com/nogibjj/as1466_week2_DE/blob/main/bmi.csv) file

## Overall dataset descriptive statistics

|       |      Age |      Height |   Weight |       Bmi |
|:------|---------:|------------:|---------:|----------:|
| count | 741      | 741         | 741      | 741       |
| mean  |  31.6181 |   1.70943   |  78.4125 |  26.3654  |
| std   |  11.6555 |   0.0859744 |  32.2545 |   9.22319 |
| min   |  15      |   1.46      |  25.9    |  12.1505  |
| 25%   |  22      |   1.67      |  63      |  22.1297  |
| 50%   |  29      |   1.721     |  72.9    |  24.1324  |
| 75%   |  40      |   1.751     |  83.3    |  27.2493  |
| max   |  61      |   2.07      | 270      |  66.3013  |

## Here are some data visualizations of data to understand relationships between variables

### Boxplots of each variable
![Boxplot](boxplots.png)



### Pairplots of correlation between numerical variables, segmented by BMI segment

![Variable Correlations](pairplot.png)

