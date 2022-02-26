# Dissertation
This repo contains my bachelor dissertation in Computer Science. It's about Artificial Intelligence, specifically about the fields of machine learning, AutoML and Meta-Learning.

## Abstract

The field of automatic machine learning (AutoML) has been highlighted as one of the main alternatives to find good solutions for complex machine learning problems. Despite the recent success of AutoML, many challenges remain. Learning AutoML is a time-consuming process and can be computationally inefficient. Meta-learning is described as the process of learning from past experiences by applying various learning algorithms on different types of data and thus reducing the time needed to learn new tasks. One of the advantages of meta-learning techniques is that they can serve as an efficient support for the AutoML process, learning from previous tasks the best algorithms to solve a certain type of problem. In this way, it is possible to speed up the AutoML process, obtaining better results in the same period of time. The objective of this thesis is to design a meta-learning strategy for generic domains in machine learning.

The implemented meta-learning proposal is capable of addressing a wide variety of tasks by selecting characteristics capable of representing the space defined by them. Furthermore, by exploring the interaction between dataset characteristics and stream structure, the proposed method is able to identify streams with good performance without performing a computationally expensive analysis. As a complementary AutoML system, AutoGOAL was chosen, which stands out for its ability to generate effective solutions for a wide range of domains, allowing you to solve a large number of tasks. AutoGOAL is used for the generation of algorithm flows to create the knowledge base and in the search for flows initialized with the designed meta-learning approach.

The meta-learning approach developed consists of the selection of a set of algorithm flows to be recommended in the initialization of the optimization process of an AutoML system. The choice of this set of streams is done using a ranking approach, in which the `k` best algorithm streams are selected for a new dataset. For this, several strategies were implemented. The experimental evaluation carried out on a large number of datasets shows that these meta-learning strategies obtain better results in terms of the algorithm flows found with respect to AutoGOAL without meta-learning, without any consideration of the specific domain or problem.