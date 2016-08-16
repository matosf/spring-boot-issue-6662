Project to showcase issue https://github.com/spring-projects/spring-boot/issues/6662

Command:
```
mvn clean compile
```

Will fail with:
```
[ERROR] diagnostic: error: cannot access org.apache.http.annotation.Immutable
  class file for org.apache.http.annotation.Immutable not found
```

Can be fixed by disabling annotation processing in pom.xml, line 62.
