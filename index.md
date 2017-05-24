# Selective data systems

We challenge a common practice in both private and public sectors of collecting vast quantities of personal information. We ask whether it is possible to build data-driven systems, such as machine learning-based personalization systems, that are more selective with the data they collect. This entails pinpointing the data that is valuable for the current and evolving workload, and either not collecting or setting aside the data that is not truly valuable.

Our vision points to leveraging and combining *training set modeling* mechanisms from machine learning (ML) as building blocks to construct selective data systems, which provide this distinction by construction. In our preliminary experience with one such system, *Pyramid*, realistic workloads running on two public datasets require less than 1% of the data to achieve accuracy and performance on par with running on the complete datasets. We explore the data protection and maintenance cost benefits of applying selectivity to data-driven systems.

## Pyramid

Our first step towards selective data systems is [Pyramid](https://github.com/columbia/pyramid.lib), a limited-exposure data management system that builds upon a particular training set modeling mechanism, called *count featurization*, to enhance data protection. As such, Pyramid uniquely introduces both the idea and proof-of-concept for leveraging training set modeling methods to instill rigor and selectivity into big data management. We integrated Pyramid into Spark Velox, a framework for ML-based targeting and personalization. We evaluate it on three applications and show that Pyramid approaches state-of-the-art models while training on less than 1% of the raw data.

### Pyramid code 

- [Pyramid](https://github.com/columbia/pyramid-release) source code with an example.

### Pyramid tech report and system

- [Tech Report (extends the S&P paper)](http://arxiv.org/abs/1705.07512)
- [S&P 2017 paper](https://roxanageambasu.github.io/publications/oakland2017pyramid.pdf)
