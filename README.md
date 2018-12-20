## Linear Modelling and Network Analysis of the Human Brain Proteome 

This repository contains analysis and results from our work evaluating protein expression data from human brain tissue exhibiting both Alzheimer's and Parkinson's neurodegenerative diseases. The final report summarizing our results and listing the differentially expressed gene candidates can be found [here](/report/report.pdf). The original data-set that used is located on [Synapse](https://www.synapse.org/#!Synapse:syn10183278/wiki/450583).

**Authors:** Ramasubramanian Balasubramanian, John Canty, Annan Deng, William Krinsman

## Summary

Log-fold protein expression values were obtained using Label-free Tandem Mass Spectrometry. For more information on the details of the experimental protocol, please consult the original publication below.

![Sample Collection](https://github.com/jtcanty/Brain-Proteome/blob/master/docs/sample_collection.png)


Detailed below is the general workflow for exploratory data analysis, processing, and modelling used in the report. 

![Data Analysis](https://github.com/jtcanty/Brain-Proteome/blob/master/docs/differential_expression_analysis.png)

We also performed weighted-correlation network analysis (WCNA) in order to identify protein expression correlations within groups of differentially identified genes. Using the list of differentially expressed genes, we identified their biological functions using the PANTHER gene ontology [database](http://www.pantherdb.org).


## References

L. Ping, D.M. Duong, L. Yin, M. Gearing, J.J. Lah, A.I. Levey, & N.T. Seyfired.  *Global Quantitative Analysis of the human brain proteome in Alzheimer's and Parkinson's Disease*. Scientific Data **5**, 180036 (2018) 
