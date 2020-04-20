# guice-betas

Unofficial BETA builds of [Google-Guice](https://github.com/google/guice) with experimental features.

These builds are deployed temporarily for community testing purposes and shouldn't be used in production.

Issues with these builds should be reported [here](https://github.com/mcculls/guice-betas/issues) rather than the upstream Guice repository.

## 4.2.4-20200419-NEWAOP-BETA

This BETA replaces CGLIB with a brand-new AOP implementation that should work better with the latest JDKs

```
    <dependency>
      <groupId>com.google.inject</groupId>
      <artifactId>guice</artifactId>
      <version>4.2.4-20200419-NEWAOP-BETA</version>
    </dependency>
```

[guice-4.2.4-20200419-NEWAOP-BETA.jar](https://mcculls.github.io/guice-betas/maven2/com/google/inject/guice/4.2.4-20200419-NEWAOP-BETA/guice-4.2.4-20200419-NEWAOP-BETA.jar)

## Maven repository

To consume these betas add the following repository definition to the `<repositories>` section of your pom.xml
```
    <repository>
      <id>guice-betas</id>
      <url>https://mcculls.github.io/guice-betas/maven2/</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
```
