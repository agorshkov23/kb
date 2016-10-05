# Apache Maven

Структура файла `$project.pom`.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project ...>
    <groupId>...</groupId>
    <artifactId>...</artifactId>
    <version>...</version>

    <properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        ...
    </properties>

    <dependencies>
        ...
    </dependencies>

    <build>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.5.1</version>
                <configuration>
                    <source>1.8</source>
                    <target>1.8</target>
                </configuration>
            </plugin>
        </plugins>
    </build>
</project>
```

Последнюю версию `maven-compiler-plugin` можно найти на [странице][last version of maven-compiler-plugin].

[last version of maven-compiler-plugin]: https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-compiler-plugin