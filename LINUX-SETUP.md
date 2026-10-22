# X4Plugin: Linux development setup

Open this directory (the one containing pom.xml) in IntelliJ IDEA as a Maven project.
Use the existing `temurin-17` project SDK (Java 17). Allow Maven import to finish.

Build from this directory:

```sh
mvn clean package
```

This is a plugin library, with no standalone application main class.
The built artifact is `target/X4Plugin-1.0-SNAPSHOT.jar`.
The restored repository has no commits or configured remote.
The old IntelliJ Java 24 setting was changed to the installed Java 17 SDK.

The original tar.gz archive remains in the parent directory as a backup.
