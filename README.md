![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Unsupervised Learning


## Introduction

Some people think unsupervised learning is boring because there isn't any specific output to predict or evaluate. Other people, especially the machine learning experts, consider unsupervised learning the future of data science because it resembles how human beings learn. Think how a kid learns what a dog is. Dad and mom don't show 100K animals and tell her which ones are dogs. Rather, the kid will keep encountering dogs in her daily experience and after a number of encounterings she will extract the common features of dogs and recognize new ones.

In unsupervised learning, the classic task is cluster analysis in which you find hidden patterns or groups in data. At most times unsupervised learning tasks are open-ended and you will need to make sense of the data without any clear-defined pathways. But if you keep training yourself and eventually become good at finding pathways out of nowhere, you'll be an established data scientist. This is why you should take unsupervised learning serious.

In this lab you segment the clients of a wholesale distributor by what they spend on six product categories. There is no answer column: you decide how to prepare the data, how many clusters to keep and what each cluster means, and you justify those decisions. You will use K-means with the elbow and silhouette methods, profile the clusters, try DBSCAN, and compare both with a PCA projection. The lab follows the **Unsupervised Learning: Clustering and PCA** lesson.

## Getting Started

Open the `main.ipynb` file in the `your-code` directory. Follow the instructions, add your code, and write your observations in the markdown cells. The data is in `data/Wholesale customers data.csv`; the other files in `data/` and the notebooks in `learning/` are optional extra material.

## Deliverables

- `main.ipynb` with your responses.

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Resources

- [DBSCAN](https://en.wikipedia.org/wiki/DBSCAN)
- [The DBSCAN Paper](https://www.aaai.org/Papers/KDD/1996/KDD96-037.pdf)
- [sklearn.datasets.make_circles](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_circles.html)
- [sklearn.datasets.make_moons](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html)
- [Wholesale Customers](https://archive.ics.uci.edu/ml/datasets/wholesale+customers)
- [The Pareto Principle](https://en.wikipedia.org/wiki/Pareto_principle)
- [Scikit-Learn Standard Scaling](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html#sklearn.preprocessing.StandardScaler)
- [Cluster Analysis External Evaluation](https://en.wikipedia.org/wiki/Cluster_analysis#External_evaluation)
- [scikit-learn user guide: Clustering](https://scikit-learn.org/stable/modules/clustering.html)
- [scikit-learn user guide: Silhouette coefficient](https://scikit-learn.org/stable/modules/clustering.html#silhouette-coefficient)

