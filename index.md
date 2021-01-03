## An Introspective Study of Cardinality Estimation in SPARQL
We performed an extensive experiments to show the ... abstract ...


### Persistent URI & Licence:
All of the data and results presented in our experimental study are available at
[https://github.com/kworkr/repo/](https://github.com/kworkr/repo/) under [Apache License 2.0](https://github.com/lemon-alt/rdf/blob/master/LICENSE) .



### How does it work?


#### 1. Generating SHACL Shapes Graph:
    Given and RDF graph, we used [shaclgen](https://pypi.org/project/shaclgen/) library to generate its SHACL shapes graph.

#### 2. Generating Shapes Statistics:
    We used Shapes Annotator component to extend SHACL shapes graph with the statistics of the RDF graph.
  
#### 3. Running Experiments:
  Explain .. TDB ... then config file .. and so on.
  
  
  ##### 1. Shapes Statistics
  
  ##### 2. Global Statistics
  
  ##### 3. Jena
  
  ##### 4. Characteristics Sets
    We used the extended characteristics sets implementation from [here](https://github.com/gmontoya/federatedOptimizer )
  ##### 5. GraphDB
    We used onto:explain ....


### Datasets, Queries and the Statistics used:
We used the following datasets, queries, and the statistics: 

Dataset | RDF Dump | Queries | Stats
------------ | ------------- | -------------| -------------
[LUBM](http://swat.cse.lehigh.edu/projects/lubm/)|[Download](http://130.226.98.152/datasets/lubm.n3)| [See LUBM Queries](https://github.com/kworkr/repo/tree/master/queries/lubmQueries) | [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/lubmStats)
[YAGO-4](http://swat.cse.lehigh.edu/projects/lubm/)|[Download](http://130.226.98.152/datasets/lubm.n3)| [See YAGO-4 Queries](https://github.com/kworkr/repo/tree/master/queries/yago-4Queries) | [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/yagoStats)
[WATDIV-100M](https://link.springer.com/chapter/10.1007/978-3-319-11964-9_13)|[Download](http://dsg.uwaterloo.ca/watdiv/watdiv.100M.tar.bz2) | [See WATDIV Queries](https://github.com/kworkr/repo/tree/master/queries/watdivQueries)| [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/watdivStats)
[WATDIV-1Billion](https://link.springer.com/chapter/10.1007/978-3-319-11964-9_13)|[Download](https://hobbitdata.informatik.uni-leipzig.de/intelligent-SPARQL-interface/) | [See WATDIV Queries](https://github.com/kworkr/repo/tree/master/queries/watdivQueries)| [Global and Shapes Statistics](https://github.com/kworkr/repo/tree/master/globalAndShapesStats/watdivStats)



  
### Evaluation Results:


### Authors:
* Annonymous 
