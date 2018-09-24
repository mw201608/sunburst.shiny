#### What is?

`Hierarchy Sunburst Plot App` is a simple web-based interface to create sunburst visulization of a network hierarchy.

#### Required input

The required input is a two-column text file with header, containing the child and parent pairs of nodes.

#### Optional input

An optional node annotation/enrichment file can be uploaded to give color scheme for the nodes. This must be a multi-column text file with header. The first column should be named `Node` which contains the node id. One column must be named `Feature` to denote the annotation or signature that the nodes are associated with or enriched for. Then one column containing the annotation term or enrichment statistics can be used to assign/compute color schemes.

#### Sample data

Please see example data from github repository for a [MEGENA module hierarchy file](https://raw.githubusercontent.com/mw201608/sunburst.shiny/master/example/hierarchy.txt), and a [module enrichment file](https://raw.githubusercontent.com/mw201608/sunburst.shiny/master/example/enrichment.tsv).


#### Disclaimer

`Hierarchy Sunburst Plot App` is made available in the hope that it will be useful, but without any warranty to the extent permitted by applicable law.
