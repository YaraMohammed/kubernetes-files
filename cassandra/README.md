1- add lables to selected nodes for the cluster
kubectl label nodes <node1> <node2> <node3> test="cassandra"

2- create the daemon set definition file 
vim daemon-set.yaml

3- in each node make new directory 
mkdir -p $HOME/data/cassandra
