# otel-jaeger-sqlserver-postgres-mysql_distributed-tracing
Script do Docker Compose para a subida de ambiente para a coleta de traces de aplicações que fazem uso do projeto Jaeger, do OpenTelemetry Collector, além de bases SQL Server, MySQL e PostgreSQL.

APIs REST utilizadas por este projeto:
- [**Contagem de acessos (.NET 9 + ASP.NET Core)**](https://github.com/renatogroffe/aspnetcore9-otel-sqlserver-postgres-mysql_apicontagem)
- [**Saudações (Node.js)**](https://github.com/renatogroffe/nodejs-otel-jaeger_apisaudacoes)
- [**Consumer da API de Contagem (Python)**](https://github.com/renatogroffe/python-otel_apiconsumocontagem)
- [**Consumer das APIs (Java + Spring + Apache Camel)**](https://github.com/renatogroffe/java-spring-camel-vscode-otel-sqlserver-postgres-mysql_consumoapis)
