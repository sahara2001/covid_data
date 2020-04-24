## CSE 5526 Project Proposal: COVID-19 Research Tool

Members: Heming Sun and Lealie Zhou

### Task Details
Recent rapid spreading of COVID-19 leads to high demand of coronavirus experts. However, keeping up with the latest progress is difficult due to lack of attention in this field. In order to help scientists get familiar with the latest results about COVID-19, we propose this project to utilize unsupervised learning and deep learning methods to understand research articles and sort out relevant papers. 
### Approach:
+ Unsupervised Learning task, because we don't have labels for the articles
+ Clustering and Dimensionality Reduction task using K-Means and PCA
+ See how well labels from K-Means classify
+ Use plain text with Tf-idf
+ Use large pretrained transformers such as BERT for document embedding
+ Utilize citation network to generate graph embedding of documents which helps finding relevant papers
### Evaluation:
+ manually label a small set of documents into clusters and use this as gold labels to compute purity and normalized mutual information between this and clustering result. 
+ have some neural network to predict this clustering result and analyze the confusion matrix. 
+ visualize the clustering result and look at them and see if it really helps doctors find relevant papers.
+ Analysis of citation network
+ Analysis of document embedding and relevant document prediction based on various similarity metric

