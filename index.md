# Selective data systems

We challenge a common practice in both private and public sectors of collecting vast quantities of personal information. We ask whether it is possible to build data-driven systems, such as machine learning-based personalization systems, that are more selective with the data they collect. This entails pinpointing the data that is valuable for the current and evolving workload, and either not collecting or setting aside the data that is not truly valuable. Our vision points to leveraging and combining train- ing set modeling mechanisms from machine learning (ML) as building blocks to construct selective data systems, which pro- vide this distinction by construction. In our preliminary experi- ence with one such system, realistic workloads running on two public datasets require less than 1% of the data to achieve ac- curacy and performance on par with running on the complete datasets. We discuss the data protection and maintenance cost benefits of applying selectivity to data-driven systems.

You can use the [editor on GitHub](https://github.com/columbia/selective-data-systems/edit/master/index.md) to maintain and preview the content for your website in Markdown files.


## Pyramid

Our first step towards selective data systems is [Pyramid](https://github.com/columbia/pyramid.lib), a limited-exposure data management system that builds upon count featurization to enhance data protection. As such, Pyramid uniquely introduces both the idea and proof-of-concept for leveraging training set minimization methods to instill rigor and selectivity into big data management. We integrated Pyramid into Spark Velox, a framework for ML-based targeting and personalization. We evaluate it on three applications and show that Pyramid approaches state-of-the-art models while training on less than 1% of the raw data.

### Pyramid code 

### Pyramid tech report and system
