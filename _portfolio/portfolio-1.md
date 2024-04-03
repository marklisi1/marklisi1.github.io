---
title: "Emission Prediction with Variable Graph Structure"
excerpt: "GNN algorithm to predict location, type, or quantity of emission based on geographic proximity to other sites. PyTorch Geometric, Pandas, Shapely"
collection: portfolio
---
This project was born out of inspiration from the [2021 Climate TRACE dataset.](https://climatetrace.org/) With the goal of predicting various factors about an emissions site, I invented a novel algorithm for the conversion of standard tabular data into a graph-structured form based on geographic proximity with a sliding hyperparameter. When used with modern graph neural networks (GNNs), my algorithms boasts a 25% performance bump from standard multi-layer perceptrons.

[Read the whole paper and associated code on Github!](https://github.com/marklisi1/dynamic-edges-gcn)

* Skills: Graph data, algorithm design, deep learning, data augmentation
* Tools: PyTorch Geometric, Pandas/GeoPandas, Shapely, NumPy
