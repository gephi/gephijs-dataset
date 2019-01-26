# Dataset

This dataset contains networks used as a benchmark for the Gephi JS experiment (FOSDEM 2019).
It has been first zipped and then splitted into tar files.
Total size unzipped: 4 GB

The files are of 4 kinds:

* Empirical networks: a few spatialized networks obtained from [SNAP](http://snap.stanford.edu/data/index.html) or from the Gephi wiki
* Test metadata: networks with increasingly large metadata
* Test order: networks with increasingly large number of nodes
* Test sizes: networks with increasingly large number of edges

### TEST METADATA

These networks have the same amount of nodes and edges: 1000 nodes and 25070. They only differ by the amount of metadata associated to the nodes.

* METADATA 1 MB
	File size: 1.5 MB due to nodes and edges
	No metadata

* METADATA 10 MB
	File size 10.8 MB due to nodes metadata
	10 node attributes

* METADATA 100 MB
	File size 95.7 MB due to nodes metadata
	100 node attributes

* METADATA 1000 MB
	File size 955.6 MB due to nodes metadata
	1000 node attributes

### TEST ORDER

These networks are "stables": they have no edges. They are used to test how many nodes can be handled. There is a network for each order of magnitude.

### TEST SIZE

These networks are random graphs generated in Gephi. They all have 14142 nodes, but with different densities corresponding to different link numbers, one for each order of magnitude.

* E 10^1
	Density: 0.0000001
	Nodes: 14142
	Edges: 12

* E 10^2
	Density: 0.000001
	Nodes: 14142
	Edges: 117

* E 10^3
	Density: 0.00001
	Nodes: 14142
	Edges: 994

* E 10^4
	Density: 0.0001
	Nodes: 14142
	Edges: 9960

* E 10^5
	Density: 0.001
	Nodes: 14142
	Edges: 100268

* E 10^6
	Density: 0.01
	Nodes: 14142
	Edges: 1000434

* E 10^7
	Density: 0.1
	Nodes: 14142
	Edges: 10003201