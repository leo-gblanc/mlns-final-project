# mlns-final-project
Machine Learning in Network Science Final Project


Code for our final project for the Machine Learning in Network Science course.
The data for this project can be dowloaded at this link: https://prim.iledefrance-mobilites.fr/fr/jeux-de-donnees/offre-horaires-tc-gtfs-idfm

This project investigates the application of machine learning techniques to network science problems, focusing on link prediction in the Paris Metro and RER transportation network. By leveraging structural properties of the network and node embeddings, we formulate the link prediction task as a supervised classification problem. We extract features based on topological information of the network and train both traditional heuristic methods and embedding-based models to predict missing links. Our results demonstrate that node2vec embeddings combined with logistic regression outperform traditional heuristic approaches in identifying potential new connections that could improve the efficiency of the transportation network. The proposed methodology achieves an ROC-AUC score of 0.61, showcasing its effectiveness in predicting missing links. Furthermore, we evaluate the impact of adding these predicted links on global network metrics, observing improvements in average path length and network efficiency.
