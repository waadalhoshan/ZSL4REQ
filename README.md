# ZSL4REQ
Experiments of ZSL Pipeline to classify requirements. 

## Contents
This repository contains the auxiliary materials used for conducting the study: Zero-Shot Learning for Requirements Classification: An Exploratory Study. The main content are:

1- The experiement results for all the three classifcation tasks: (1) FR/NFR: classification functional requirements vs non-
functional requirements; (2) NFR: identification of NFR classes; (3) Security: classification of security vs non-security requirements.

2- Colab Notebook for running/replicating the conducted experiments


## Abstract


Context and motivation: Requirements engineering (RE) researchers have been experimenting machine learning (ML) and deep learning (DL) approaches for a range of RE tasks, such as requirements classification, requirements tracing, ambiguity detection, and modelling. Question/problem: Most of today’s ML/DL approaches are based on supervised learning techniques, meaning that they need to be trained using annotated datasets to learn how to assign a class label to sample items from an application domain. This constraint poses an enormous challenge to RE researchers, as the lack of annotated datasets makes it difficult for them to fully exploit the benefit of advanced ML/DL technologies. Principal ideas/results: To address this challenge, this paper proposes a approach that employs the embedding-based unsupervised Zero-Shot Learning (ZSL) technique to perform requirements classification. We focus on the classification task because many RE tasks can be framed as classification problems. In this study, we demonstrate our approach for three tasks. (1) FR/NFR: classification functional requirements vs nonfunctional requirements; (2) NFR: identification of NFR classes; (3) Security: classification of security vs non-security requirements. The study shows that the ZSL approach achieves an F1 score of 0.66 for the FR/NFR task. For the NFR task, the approach yields F1∼ 0.72−0.80, considering the most frequent classes. For the Security task, F1 ∼ 0.66. All of the aforementioned F1 scores are achieved with zero-training efforts. Contribution: This study demonstrates the potential of ZSL for requirements classification. An important implication is that it is possible to have very little or no training data to perform multiple tasks. The proposed approach thus contributes to the solution of the longstanding problem of data shortage in RE.
