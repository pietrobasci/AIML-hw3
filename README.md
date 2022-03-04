# AIML-hw3

Third Assignment for the course "Machine Learning and Artificial Intelligence" @Politecnico di Torino.

Domani Adversarial Neural Network based on AlexNet.

* *Main algorithms and techniques:* DANN, AlexNet, Transfer Learning, Data Augmentation.
* *Evaluation metrics:* Accuracy (Cross-Domain Validation).
* *Programming language and main libraries:* Python, Pytorch.

### Abstract

The purpose of this homework is to implement a Domain Adversarial Neural Network (DANN) using AlexNet to classify images belonging to different domains. The dataset considered is the PACS dataset, which consists of 4 different domains: Photo, Art painting, Cartoon and Sketch which so far considers the largest domain shift as it is from the different image style depictions.
<br>Domain Adaptation is a technique that aims to improve performance in problems where training and test data come from similar but different distributions. The idea behind the model used is that, in order to achieve good performance on new distribution, predictions must be made based on features that cannot discriminate between the training (source) and test (target) domains. The model used is Domain Adversarial Neural Network (DANN) built using AlexNet.

<br>For more details see [*AIML-hw3.pdf*](AIML-hw3.pdf).
