# Java 1.7 JRE Image

This is a small, [Alpine Linux](http://www.alpinelinux.org/) based Docker image
that contains the Java 1.7 JVM. It's useful for executing Java bytecode, but note
that it doesn't contain the JDK, so you can't use it to compile Java code.

## Using

```sh
docker run -it --rm iron/java:1.7 java -version
```
