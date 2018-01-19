# maven-parent

Apache Maven parent pom

## Usage

```xml
  <repositories>
    <repository>
      <id>nakahiro386-parent-pom</id>
      <name>nakahiro386 parent pom</name>
      <url>https://nakahiro386.github.io/maven-parent/repo</url>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
  </repositories>

  <parent>
    <groupId>io.github.nakahiro386</groupId>
    <artifactId>parent</artifactId>
    <version>${parent.version}</version>
    <relativePath />
  </parent>
```

## deploy

```sh
$ mvn release:prepare

$ mvn release:perform
```

## License

MIT License

## Author

nakahiro386
