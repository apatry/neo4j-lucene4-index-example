Sample project using Lucene v4 with Neo4j
=========================================

This project runs [a tutorial example](http://docs.neo4j.org/chunked/milestone/tutorials-java-embedded-index.html) with lucene 4 using [neo4j-lucene4-index](https://github.com/apatry/neo4j-lucene4-index).

Once `neo4j-lucene4-index` is installed, you can run this example using:

```
mvn compile
mvn exec:java
```

If everything works fine, the output should contain:

```
Users created
The username of user 45 is user45@neo4j.org
Shutting down database ...
```
