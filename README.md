# Paper: Global Explanation of Tree-Ensembles Models Based in Item Response Theory.

Autors: 

José Ribeiro - site: https://sites.google.com/view/jose-sousa-ribeiro

Lucas Cardoso - site: http://lattes.cnpq.br/9591352011725008

Raíssa Silva - site: https://sites.google.com/site/silvarailors

Vitor Cirilo - site: https://sites.google.com/site/vitorciriloaraujosantos/

Níkolas Carneiro - site: https://br.linkedin.com/in/nikolas-carneiro-62b6568

Ronnie Alves (Leader) - site: https://sites.google.com/site/alvesrco

## Absrtact

Explainable Artificial Intelligence - XAI, is a sub-area of ​​Machine Learning whose main objective is the study and development of techniques aimed at explaining black box computational models, that is, models that have limited self-explanation capacity. predictions. In recent years, researchers in this area have formalized proposals and developed new measures that aim to explain how black box models make certain predictions. This is considered, by the research community, an area of ​​research in vogue, as it is increasingly possible to notice intelligent systems based on black box machine learning models present in the day-to-day society, also growing the need to explain them, especially when the prediction problem to be solved involves a sensitive context. In previous publications, evidence was found of how model complexity (dataset and algorithm) affects global explanations based on ranks generated by XAI Ciu, Dalex, Eli5, Lofo, Shap and Skater measures. Since, in the present study, the existence of tree-ensemble-based models that are easier to explain and others that are more difficult was verified, showing the needs and limitations of the current measures of explainability. In this sense, this research aims to present a new XAI measure called Explainable based on Item Response Theory - eXirt, capable of explaining tree-ensemble black box models using the properties (guessing, difficulty and discrimination) of Response Theory. to the Item - IRT, a technique that is already consolidated in other areas. For this, a benchmark was created from 40 different datasets and 2 different algorithms (Random Forest and Gradient Boosting) generated 6 different ranks of explainability through XAI measures already known by the computing community, along with 1 rank of purity. of data and 1 rank of the proposed XAI measure, eXirt, thus totaling 8 global ranks for each model created (a total of 640 ranks). The results showed that the eXirt measure presented different ranks from the other ranks analyzed, which demonstrates that the methodology defended here generates a set of global explanations of attributes of the tree-ensemble models not yet explored by the current XAI measures, either for the model's easiest to explain or even the most difficult.

## This repository was created to contain all additional information from the article "Global Explanation of Tree-Ensembles Models Based in Item Response Theory", for reproducibility purposes.

Description for execution:
All data regarding the reproducibility of this work can be found in this repository.

  - Cluster 0: all datasets, performance graphs, models and analyzes coming from cluster 0 data.

  - Cluster 1: all datasets, performance graphs, models and analyzes coming from cluster 1 data.

  - eXirt - Notebook - v0.1.ipynb: all the source code used to execute the experiments presented in this research. It should be noted that this notebook is properly commented, documented and separated into sections for better understanding in case of an execution.

  - df_dataset_properties: dataset with all 15 properties analyzed in the Multiple Correspondence Analysis - MCA;
  
  - Analisys_of_Cluster_by_eXirt.ipynb: all analysis of item parameter values for the two clusters;
  
  - Just eXirt - Execution example.ipynb: simple execution of eXirt.

To run the notebook XAI - IRT Notebook.ipynb, it is suggested to use Google Colab, for a better and faster execution of the tool.
