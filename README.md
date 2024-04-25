# AutoML Optimization for Glioblastoma Multiforme Data Analysis

This repository hosts the code and models from our capstone project at the Knight Foundation School of Computing and Information Sciences, Florida International University. Our project, under the guidance of Dr. Giri Narasimhan and mentorship of Dr. Ananda Mondal, involved developing a robust AutoML framework to improve the performance of neural networks analyzing multi-omics glioblastoma data.

**Highlights:**

Application of AutoML techniques to optimize a CNN initially yielding AUC of 0.76, achieving a marked improvement in validation accuracy post-tuning.
Exploration of hyperparameter and layer morphing strategies, using approaches like Bayesian Optimization, Random Search, and Hyperband, to enhance model efficiency and combat overfitting.
Layer morphing was adjusted across trials to optimize the model without excessive complexity, successfully addressing overfitting issues detected in earlier iterations.

**Repository Contents:**

Code for preprocessing and mining multi-omics data including mRNA expression, CNV, and DNA methylation from datasets like TCGA.
Utilization of the KEGG database for pathway analysis.
Jupyter notebooks detailing the hyperparameter tuning and neural architecture search processes.
Results and observations from various trials showcasing model improvements and challenges addressed, including proof of overfitting and subsequent remediation.

**Outcome:**

The project successfully demonstrated the potential of AutoML in the medical field, specifically in analyzing complex data for GBM. An average improvement of 15% was observed across three trials, with the best results obtained in the final trial.
We invite the community to explore our findings, replicate our models, and contribute to furthering research in this crucial domain.
