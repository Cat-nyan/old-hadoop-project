## Running
``` bash
mvn package assembly:single # this will bundle dependencies, we actually don't have any, but good to set up.
hadoop jar target/java-mapreduce-1.0-SNAPSHOT-jar-with-dependencies.jar
```

