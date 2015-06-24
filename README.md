# Repository

The repository project hosts a maven repository which can be referenced by
external maven projects by adding:

```xml
  <repositories>
    <repository>
      <id>com.github.bjconlan</id>
      <url>https://raw.github.com/bjconlan/repository/release</url>
    </repository>
  </repositories>
```

or

```groovy
  repositories {
    maven { url 'https://raw.github.com/bjconlan/repository/release' }
  }
```

to their projects `pom.xml` or `build.gradle` project definitions.
