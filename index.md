### This work will be presented at [ICML'22](icml.cc) Workshop on [ML in Computational Design](http://mlcompdesign.github.io/).
![GIF](/mlcd22-gnn4robots/docs/assets/gnn4robots-icml22mlcd.gif)

## Abstract
We propose a learning framework to find the representation of a robot's kinematic structure and pose embedding spaces using graph neural networks (GNN). Finding a compact and low-dimensional embedding space for complex phenomena is a key for understanding its behaviors, which may lead to a better learning performance, as we observed in other domains of images or languages. However, although numerous applications deal with various types of structural and motion data, the embedding of the generated data has been relatively less studied by roboticists. To this end, our work aims to learn embeddings for two types of robotic data: the robot's design structure, such as links, joints, and their relationships, and the pose data, such as kinematic joint positions. Our method exploits the tree structure of the robot to train appropriate embeddings to the given robot data. To avoid overfitting, we formulate multi-task learning to find a general representation of the embedding spaces. We evaluate the proposed learning method on a robot with a simple linear structure and visualize the learned embeddings using t-SNE. We also study a few design choices of the learning framework, such as network architectures and message passing schemes.

### Learn more here
[\[arXiv\]](https://arxiv.org/abs/2109.07543)
[\[PDF\]](/mlcd22-gnn4robots/docs/assets/gnn4robots-icml22mlcd.pdf)
[\[Video (MP4)\]](/mlcd22-gnn4robots/docs/assets/icml22-mlcd-gnnrobot.mp4)
[\[Poster (PDF)\]](/mlcd22-gnn4robots/docs/assets/gnn4robots-icml22mlcd-poster.pdf)
![\[Poster\]](/mlcd22-gnn4robots/docs/assets/gnn4robots-icml22mlcd-poster.jpg)

### Contact
[taerykim@gatech.edu](mailto:taerykim@gatech.edu)
