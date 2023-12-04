# ice-atlas-data

[Catamount Hardware](https://catamounthardware.com)

```bash
./mvnw -DskipTests -Djib.platform-arch=arm64 -Djib.to.tags="ice-atlas" package jib:dockerBuild --file pom.xml
```
