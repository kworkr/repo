## An Introspective Study of Cardinality Estimation in SPARQL
We performed an extensive experiments to show the ...


### Persistent URI, Licence:
All of the data and results presented in our evaluation are available online at
[https://github.com/kworkr/repo/](https://github.com/kworkr/repo/) under [Apache License 2.0](https://github.com/lemon-alt/rdf/blob/master/LICENSE) .



### Datasets, Queries and the Stats used:
We used the following datasets, queries, and the statistics: 

Dataset | RDF Dump | Queries | Stats
------------ | ------------- | -------------| -------------
[LUBM](http://swat.cse.lehigh.edu/projects/lubm/)|[Download](http://130.226.98.152/datasets/lubm.n3)| [See LUBM Queries](https://github.com/kworkr/repo/tree/master/queries/lubmQueries) | [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/lubmStats)
[YAGO-4](http://swat.cse.lehigh.edu/projects/lubm/)|[Download](http://130.226.98.152/datasets/lubm.n3)| [See YAGO-4 Queries](https://github.com/kworkr/repo/tree/master/queries/yago-4Queries) | [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/yagoStats)
[WATDIV-100M](https://link.springer.com/chapter/10.1007/978-3-319-11964-9_13)|[Download](http://dsg.uwaterloo.ca/watdiv/watdiv.100M.tar.bz2) | [See WATDIV Queries](https://github.com/kworkr/repo/tree/master/queries/watdivQueries)| [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/watdivStats)
[WATDIV-1Billion](https://link.springer.com/chapter/10.1007/978-3-319-11964-9_13)|[Download](https://hobbitdata.informatik.uni-leipzig.de/intelligent-SPARQL-interface/) | [See WATDIV Queries](https://github.com/kworkr/repo/tree/master/queries/watdivQueries)| [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/watdivStats)


### How does it work?

#### 1. Generating SHACL Shapes Graph:
    Given and RDF graph, we used [shaclgen](https://pypi.org/project/shaclgen/) library to generate its SHACL shapes graph.

#### 2. Generating Shapes Statistics:
    We used Shapes Annotator component to extend SHACL shapes graph with the statistics of the RDF graph.
  
#### 3. Running Experiments:
  Running experiments using
  1. Item 1
  1. Item 2
  1. Item 3
     1. Item 3a
     1. Item 3b
  


For CS:
https://github.com/gmontoya/federatedOptimizer 
### Evaluation results:


### Authors:
* Annonymous 
