##  Salary API
***


| Author | Created on  | Version    | Last Updated by | Last Updated on |
| -------- | ------- | -------------- | --------------| ---------------- |
| Harshit Singh  | 10-01-2024  | 1.0   | Harshit Singh | 10-01-2024 |

##  Purpose
Serve the request regarding salary from frontend. 
***

## Pre-Requisites

- [Scylla](https://website-name.com 'Scylla') 
( [For Linux](https://opensource.docs.scylladb.com/stable/getting-started/install-scylla/install-on-linux.html 'Install Scylla in Linux') )
- [Redis](https://redis.io/ 'Redis') 
- [Maven](https://maven.apache.org/ 'maven')
- [Migrate](https://github.com/golang-migrate/migrate 'migrate')

## MAVEN cmds:

```shell
mvn dependency:copy-dependencies 
```

```shell
mvn test 
```

```shell
mvn package
```

```shell
java -jar target/salary-0.1.0-RELEASE.jar
```