# StopWatch MCP

```bash
sdk env
./mvnw clean verify

jbang ./src/main/java/info/jab/jbang/MCPStopWatch.java

jbang stopwatch-mcp@jabrena

docker build -t stopwatch-mcp -f Dockerfile .
docker run stopwatch-mcp

./mvnw versions:display-dependency-updates
./mvnw versions:display-plugin-updates
./mvnw versions:display-property-updates
```
