---
title: "Emission Prediction with Variable Graph Structure"
excerpt: "GNN algorithm to predict location, type, or quantity of emission based on geographic proximity to other sites. PyTorch Geometric, Pandas, Shapely"
collection: portfolio
---
As the world continues to industrialize, it becomes more and more important to understand the effects
of human-generated emissions on our planet. Accurate and timely climate modeling and prediction
are essential for addressing pressing environmental and societal challenges, such as extreme weather
events, sea-level rise, and food security.

Traditional climate models often rely on grid-based representations of Earth’s surface and atmosphere,
which can lead to challenges in capturing fine-grained spatial dependencies and intricate climate
phenomena. In contrast, graph neural networks lend themselves well to tasks involving structured data,
such as geographic emission records. This project introduces a novel approach to representing
geographic data in a graph format based on physical proximity - we are then able to optimize accuracy in node prediction tasks by tuning the distance threshold required to denote an edge.

Through a series of experiments, this project highlights a clear improvement in the accuracy of a graph convolutional network over the performance of a multi-layer perceptron.  Both regression and classification tasks saw improvement by converting standard tabular data into a graph-structured format based on physical proximity. Varying the distance threshold required to draw an edge seems to have limited effect on the ultimate result of the model, but affects the rate of convergence. Overall, the merit of converting standard tabular data to an artificially structured dataset is made clear by significant improvements in performance on classification and regression tasks.

[Read the whole paper and associated code on Github!](https://github.com/marklisi1/dynamic-edges-gcn)
