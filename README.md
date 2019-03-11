### Hierarchy Sunburst Plot App

#### What is?

[`Hierarchy Sunburst Plot App`](https://network.shinyapps.io/sunburst/) is a versatile and user-friendly web application for creating sunburst visulization of a network hierarchy. It is developed based on R packages [NetWeaver](https://github.com/mw201608/NetWeaver) and shiny.

#### Required input

The required input is a tab-delimited text file with header, containing the child and parent pairs of nodes.

#### Optional input

An optional node annotation/enrichment file can be uploaded to give color scheme for the nodes. This must be a multi-column tab-delimited text file (either a long or a wide-shape data.frame) with header. One column containing the annotation term or enrichment statistics can be used to assign/compute color schemes.

#### Sample data

Please see example data (long-shape data.frame) from github repository for a [MEGENA module hierarchy file](https://raw.githubusercontent.com/mw201608/sunburst.shiny/master/example/hierarchy.txt), and a [module enrichment file](https://raw.githubusercontent.com/mw201608/sunburst.shiny/master/example/enrichment.tsv). See below the example output from this data.

<img src="https://github.com/mw201608/sunburst.shiny/blob/master/ex1.png" width="500px">

#### Disclaimer

`Hierarchy Sunburst Plot App` is made available in the hope that it will be useful, but without any warranty to the extent permitted by applicable law.
