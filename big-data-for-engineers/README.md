# Big Data for Engineers

Semester: Spring semester 2020

Lecturer: Prof. Ghislain Fourny

Website: https://archive-systems.ethz.ch/courses/spring2020/bigdataforeng

## Summary

This course gives an overview of database technologies and of the most important database design principles that lay the foundations of the Big Data universe.

We take the monolithic, one-machine relational stack from the 1970s, smash it down and rebuild it on top of large clusters: starting with distributed storage, and all the way up to syntax, models, validation, processing, indexing, and querying. A broad range of aspects is covered with a focus on how they fit all together in the big picture of the Big Data ecosystem.

- physical storage: distributed file systems (HDFS), object storage(S3), key-value stores

- logical storage: document stores (MongoDB), column stores (HBase)

- data formats and syntaxes (XML, JSON, RDF, CSV, YAML, protocol buffers, Avro)

- data shapes and models (tables, trees)

- type systems and schemas: atomic types, structured types (arrays, maps), set-based type systems (?, *, +)

- an overview of functional, declarative programming languages across data shapes (SQL, JSONiq)

- the most important query paradigms (selection, projection, joining, grouping, ordering, windowing)

- paradigms for parallel processing, two-stage (MapReduce) and DAG-based (Spark)

- resource management (YARN)

- what a data center is made of and why it matters (racks, nodes, ...)

- underlying architectures (internal machinery of HDFS, HBase, Spark)

- optimization techniques (functional and declarative paradigms, query plans, rewrites, indexing)

- applications.