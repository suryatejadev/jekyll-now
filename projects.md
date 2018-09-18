---
layout: page
title: Projects
permalink: /projects/
---

This page contains brief overviews of the projects I have been working on.

1. [**Thyroid Segmentation**](https://suryatejadev.github.io/thyroid_segmentation/) ([code](https://github.com/suryatejadev/thyroid_segmentation))  
- Worked on segmentation of thyroid nodules in ultrasound images. Dataset used: [Open-CAS Ultrasound Dataset](http://opencas.webarchiv.kit.edu/?q=node/29)
- Developed models using Keras for the task employing architectures like U-Nets, densenets, and dilated convolutions and achieved an average dice coefficient of 85%. <br/><br/>

2. [**Medical Segmentation Decathlon 2018**](https://suryatejadev.github.io/medseg_decathlon/) ([code](https://github.com/suryatejadev/medseg_decathlon))  
- This is my source code for the [Medical Segmentation Decathlon](http://medicaldecathlon.com/), a generalizable 3D segmentation challenge. The objective of the competition is to develop a single segmentation model that can segment images of 10 different organs, namely, liver, brain, hippocampus, lung, prostrate, cardiac, pancreas, colon, hepatic vessels and spleen.
- My approach to this problem involved two steps. First, I trained a model to classify the organ of the input image. Using this output, I generated a conditional map, which is an image with the same intenstiy for all pixels. Each organ is assigned a specific intensity value. This map acts as a conditioning layer to the following segmentation model, and is appended to the input image. A multi-label segmentation model is then trained using the concatenated input image. 
- All the models are implemented using Keras. <br/><br/>

3. [**Reinforcement Learning Agents**](https://suryatejadev.github.io/RL_agents/) ([code](https://github.com/suryatejadev/RL_agents))  
- This code contains the Python implementations of two RL agents SARSA and Q-Learning, and the Mountain car environment. <br/><br/>

4. [**Genetic Mutation Classification**](https://suryatejadev.github.io/classification_geneticMutation/) ([code](https://github.com/suryatejadev/classification_geneticMutation))  
- This project is an individual project done in the course 'COMPSCI 682 Neural Networks: A modern introduction'. It is a NIPS 2017 Kaggle competition [Personalized Medicine: Redefining Cancer Treatment](https://www.kaggle.com/c/msk-redefining-cancer-treatment).
- The objective of this project is to build an automated multi-class classification system for the prediction of the type of cancer caused by the genetic mutations. The classification is based on clinical text evidence, which in the form of biomedical publications. 
- Experiments are conducted with several word embeddings techniques (bag of words, Word2Vec, Doc2Vec, etc), data imbalance mitigation methods and classification models (logistic regression, ANN, SVM, random forest, 1D CNN, LSTM, etc). <br/><br/>

5. [**Multi-Class Classification Framework**](https://suryatejadev.github.io/framework_classification/) ([code](https://github.com/suryatejadev/framework_classification))  
* This contains the source code for a Keras-based framework that can be used for any multi-class classification tasks. 
* It includes the following: 
	* Classification Models: ANN, SVM, random forest, decision trees. 
	* Data Expansion Methods: Oversampling, [SMOTE](https://arxiv.org/abs/1106.1813).
	* Evaluation Metrics: Accuracy, sensitivity, specificity, area under the ROC curve, Positive and negative predictive values.  
	* Visualization Methods: [t-SNE](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding) <br/><br/>

