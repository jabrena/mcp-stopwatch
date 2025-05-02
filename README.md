# StopWatch MCP

```bash
sdk env
./mvnw clean verify

jbang ./src/main/java/info/jab/jbang/MCPStopWatch.java

jbang mcp-calculator@jabrena

docker build -t mcp-stopwatch -f Dockerfile .
docker run mcp-stopwatch

./mvnw versions:display-dependency-updates
./mvnw versions:display-plugin-updates
./mvnw versions:display-property-updates
```