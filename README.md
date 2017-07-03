# Groovy Gradle Fatjar example

An example of how to create a basic Groovy project that uses Gradle with the Shadow plugin to create a "fat jar" of the whole project (a jar with all its dependencies in it). 


Invoke with:

```
    gradle shadowJar
```


Execute the resulting jar with:

```
    java -jar build/libs/groovy-gradle-fatjar-example-all.jar
```
