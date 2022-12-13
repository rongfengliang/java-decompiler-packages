# java-decompiler

## command

```code
docker run -it -v $PWD/src:/src -v $PWD/dest:/dest  dalongrong/eclipse-temurin:19.0.1_10-jdk-focal-java-decompiler java -cp /opt/java-decompiler.jar org.jetbrains.java.decompiler.main.decompiler.ConsoleDecompiler /src/dremio-ce-sabot-kernel-23.1.0-202211250136090978-a79618c7.jar /dest
```