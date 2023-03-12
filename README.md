# QML-HEP
Tasks for QML-HEP GSOC 2023 projects

## Task 2 (Answers)

PointNet and Graph Convolutional Networks (GCN) architectures that work well with point cloud data can be used to classify jets as quarks or gluons. PointNet uses an MLP neural network to extract features directly from raw point cloud data. GCN is based on graphs, which represent point cloud data as a network of nodes and edges. GCN extracts feature using convolutional operations and aggregate them to produce a global feature vector that represents the entire graph.

When deciding which architecture to use, we must consider the dataset's characteristics as well as the desired performance metrics, such as accuracy, precision, recall, and F1 score.

Both PointNet and GCN have been shown to achieve high accuracy in point cloud classification tasks in terms of performance. PointNet, on the other hand, is more computationally efficient and can handle larger point clouds than GCN. GCN, on the other hand, can handle more complex graph structures and capture node relationships better than PointNet. 

To summarise, both PointNet and GCN can be used to classify jets as quarks or gluons. PointNet is more computationally efficient and better suited for dealing with larger point clouds, whereas GCN is better suited for dealing with more complex graph structures and capturing node relationships. The architecture chosen is determined by the task's specific requirements and the characteristics of the dataset.

