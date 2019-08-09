# Greeter 

Testing application for learning Spring framework with Maven

```bash
# compile
mvn -e compile

# package
mvn -e clean package

# run
java -jar ./target/*.jar

# interact
curl 'http://localhost:8080/greeting' | jq
curl 'http://localhost:8080/greeting?name=test' | jq
```
