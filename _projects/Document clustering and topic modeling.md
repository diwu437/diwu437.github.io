---
title: "Document clustering and topic modeling"
excerpt: "<img src='/images/LDA.png'>"
collection: projects
---

In this project, I used unsupervised learning models to cluster unlabeled documents into different groups and identify their latent topics/structures.
The data consist over 900k customer reviews from a watch retailer. 
For the first goal, I grouped customer reviews with k-means by their TF-IDF. Then I will select 6 most important words with highest importance. The “importance” here refer to highest TF-IDF which come from the center of each cluster. 
For the second goal, I used Latent Dirichlet Allocation model to find latent topics and assign them to each document. Lastly, I selected top 14 key words for each topics.  

