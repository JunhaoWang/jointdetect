# JointDetect

JointDetect is a novel joint autoencoder based solution for detecting anomalous user groups on Twitter, especially those engaging in Information Operations. It does so through the following:

  - Embed users onto Euclidean space based on follower network and hashtag usage
  - Cluster user embeddings using DBSCAN
  - Identify anomalous clusters with high-network-density cluster-induced followership subgraph

### Installation

JointDetect requires CUDA GPU, Python3, and Jupyter Notebook to run.

Install the dependencies and start the notebook.

```sh
$ cd jointdetect
$ pip3 install -r requirements.txt
$ jupyter notebook
```