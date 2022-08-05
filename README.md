# ZSL4REQ
Experiments of ZSL Pipeline to classify requirements. 

This repository contains the auxiliary materials used for conducting the study: Zero-Shot Learning for Requirements Classification: An Exploratory Study.

Contents:

1- The experiement results for all the three classifcation tasks: (1) FR/NFR: classification functional requirements vs non-
functional requirements; (2) NFR: identification of NFR classes; (3) Security: classification of security vs non-security requirements.

2- Colab Notebook for running the experiments


#Abstarct


Context and motivation:} 
%Advances in Machine Learning (ML) and Deep Learning (DL) technologies have transformed the field of Natural Language Processing (NLP), making NLP more practical and accessible.  
%Motivated by these exciting developments,
Requirements engineering (RE) researchers have been experimenting machine learning (ML) and deep learning (DL) approaches for a range of RE tasks, such as requirements classification, requirements tracing, ambiguity detection, and modelling.
\textit{Question/problem:} Most of today's ML/DL approaches are based on \textit{supervised} learning techniques, meaning that they need to be trained using annotated datasets to learn how to assign a class label to sample items from an application domain. This constraint poses an enormous challenge to RE researchers, as the lack of 
%requirements datasets in general and 
annotated datasets %in particular, 
makes it difficult for them to fully exploit the benefit of advanced ML/DL technologies. 
\textit{Principal ideas/results:} To address this challenge, this paper proposes a approach that employs the embedding-based \textit{unsupervised} Zero-Shot Learning (ZSL) technique to perform requirements classification. 
%We build several classification models using ZSL. 
We focus on the classification task because many RE tasks can be framed as classification problems.  
%by a large number of available ML/DL methods. 
In this study, we demonstrate our approach for three tasks. (1) FR/NFR: classification functional requirements vs non-functional requirements; (2) NFR: identification of NFR classes; (3)~Security: classification of security vs non-security requirements. %We build several classification models using ZSL. 
%ZSL supports learning without domain-specific training data, thus solving the lack of annotated datasets typical of RE. AlE: Commented out because we repeat this later.
%\hl{start-text edited by Waad: Ale: maybe this can go in the introduction? I think there is a space limit for abstract} 
The study shows that the ZSL approach achieves an F1 score of 0.66 for the FR/NFR task.  
%with precision rate of 0.71 in detecting functional characteristics of a requirement. 
For the NFR task, the approach yields F1$\sim 0.72 - 0.80$, considering the most frequent classes. For the Security task, 
%for the FR/NFR task. 
%for classifying most frequent NFR requirements: usability, security, operational, and performance requirements.
%The promising results of applying ZSL approach is also achieved in the  Security task with an overall 
F1 $\sim 0.66$.
%for the entire security dataset, and F1$\sim 0.63-0.78$ %for the binary classification task 
%on a part of the dataset. 
All of the aforementioned F1 scores are achieved with zero-training efforts. %\hl{end-text} 
\textit{Contribution:} This study demonstrates the potential of ZSL for requirements classification. 
%The promising results of this study pave the way for further investigations and large-scale studies. 
An important implication  is that it is possible to have very little or 
no training data to perform multiple tasks. The proposed approach thus contributes to the solution of the long-standing problem of data shortage in RE. 

