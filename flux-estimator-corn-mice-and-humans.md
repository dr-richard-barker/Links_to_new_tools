# Flux estimator (corn, mice and humans)

{% embed url="http://scflux.org/" %}

### About

FLUXestimator is the first web server to estimate cell-/sample-wise metabolic fluxome (the flux distribution of the whole metabolic network) by using single-cell RNA-seq or general transcriptomics data. The methods encoded in FLUXestimator is named single cell flux estimation analysis ([scFEA](https://genome.cshlp.org/content/early/2021/07/22/gr.271205.120.abstract)), which is based on a novel graph neural network architecture (Alghamdi and Chang et al. Genome Research 2021, highlighted by RECOMB, ICIBM, and ENAR). To the best of our knowledge, scFEA (and FLUXestimator) is the first and only method can estimate sample-wise flux distribution of a metabolic network in single cell resolution. scFEA utilizes a factor graph base representation of metabolic network and a self-constrained graph neural network model for flux estimation, by assuming (1) metabolic flux can be modeled as a neural network of the genes involved in neighboring reactions, and (2) minimization of the flux imbalance of intermediate metabolites. The methods have been validated on two matched scRNA-seq and metabolomics data and multiple independent scRNA-seq, tissue and spatial transcrtipomics data. The input of FLUXestimator is a transcriptomics data and user selected metabolic network and analysis parameters. The outputs include predicted sample wise fluxome and metabolic variations.

Abnormal metabolic states have been observed in almost all human diseases. Given the pervasive role of metabolism in essentially every aspect of the disease pathology, an accurate and refined characterization of metabolic alterations and inference of their causes or downstream effects could have far-reaching impact in our knowledge on the basis of disease biology, clinical diagnosis and prevention, and disease management. Here FLUXestimator provides a unique capability to leverage the high resolution multi-omics data and the stochiometric relations of the metabolic network, to characterize the dynamics and context specificity of metabolic characteristics.

We anticipate the applications of FLUXestimator could increase our understanding in (1) identification of key metabolic reprogramming and causes, (2) the impact of metabolic abnormalities to other biological characteristics, (3) development of new systems biology analysis of metabolic abnormalities to improve precision medicine such as biomarker and drug target prediction.

An introduction of how to interpret and utilize the outputs of FLUXestimator to improve the analysis of scRNA-seq or general transcriptomics data is also provided in [tutorial](http://scflux.org/document2/).

scFEA has been highlighted in RECOMB, ISCA, ICIBM, and ENAR. For more details, please see our presentation video at this [link](https://www.youtube.com/watch?v=-S8ouz2F-Rk).

This website is free and open to all users and there is no login requirement.

[http://scflux.org/](http://scflux.org/)
