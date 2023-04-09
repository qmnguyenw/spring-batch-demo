# Spring Boot with Spring Batch Example 1
## Load CSV to DB
- `http://localhost:8081/load` - Trigger point for Spring Batch
- `http://localhost:8081/h2-console` - H2 Console for querying the in-memory tables.

## H2 Config
- `testdb` - Database.
- `sa` - User
- `password` - Password.
- `jdbc:h2:E:\Working\spring-demo-project\spring-batch-example-1\mem\testdb` - JDBC URL

// TODO: add mq (error handle, processing)