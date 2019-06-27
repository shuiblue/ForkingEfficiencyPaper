# FSE19-ForkingEfficiencyPaper

[![DOI](https://zenodo.org/badge/192971904.svg)](https://zenodo.org/badge/latestdoi/192971904)

Appendices, data sets, and R scripts for:

```
"What the Fork: A Study of Inefficient and Efficient Forking Practices in Social Coding. 
Shurui Zhou, Bogdan Vasilescu, Christian Kästner.  Proceedings of the 27th ACM Joint 
European Software Engineering Conference and Symposium on the Foundations of 
Software Engineering (ESEC/FSE), 2019.
```

## R scripts

You can run the R scripts on the CSV files in the repository to estimate the different regression models we report on in the paper.

## Operationalization of Ratio of contributing forks (Figure 2)

Please refer to the source code in repo: https://github.com/shuiblue/GithubScript/blob/master/src/Commit/GraphBasedAnalyzer.java

## Detecting if the PR is duplicate

Please refer to the patterns we designed:
https://github.com/shuiblue/GithubScript/blob/master/src/Util/IO_Process.java#L1808-L1863
