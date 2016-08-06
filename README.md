# Instrumentation

Sample program to demonstrate Instrumentation using Java Agents

STEP 1 - Goto javaagent folder and run mvn clean install to generate the jar file
STEP 2 - Once the Jar generated, execute the Java app by passing the "javaagent" jar as VM arguments

-javaagent:{$PATH}/memoryagent-0.0.1-SNAPSHOT.jar
