Project folder to deploy three docker contains via docker-compose.

Project consists of Redis with keyspace and events notification enabled, a sbt akka-http app that uses sbt-native-packager to create a docker image and nginx container for management of http connection.