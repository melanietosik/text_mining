# Text mining in Java

## Run

```
$ mkdir bin
$ export CLASSPATH=bin/pa/tfidf/:bin:lib/*:.
$ javac -d bin -sourcepath src src/pa/tfidf/Pipeline.java
$ java pa.tfidf.Pipeline <data_folder> 2> /dev/null
```