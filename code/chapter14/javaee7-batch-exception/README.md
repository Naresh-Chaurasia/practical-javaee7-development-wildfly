Basic job example with Exception Listener
=====================================
Example taken from [Practical Java EE 7 Development using WildFly application server](http://www.itbuzzpress.com/ebooks/java-ee-7-development-on-wildfly.html)

This example demonstrates the basic usage of Batch API with a with a Skippable exception listener class

###### Install the CSV file in the location specified by your job.xml (in this example /tmp) 
```shell
cp input.csv /tmp
```

###### Build and Deploy
```shell
mvn clean install wildfly:deploy  
```

###### Test
```shell
http://localhost:8080/javaee7-batch-exception/
```
 
