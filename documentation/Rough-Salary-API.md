Port 7199
here used 9042

create keyspace, table  
edit src/main/resources/application.yml
edit test/main/resources/application.yml
edit migration.json


MAVEN DEPENDIES
mvn dependency:copy-dependencies

java -jar target/salary-0.1.0-RELEASE.jar


sudo apt update 
sudo apt install openjdk-17-jre 
sudo apt install maven
sudo apt install redis-server
 sudo apt install jq
 sudo apt install golang

install scylladb = https://opensource.docs.scylladb.com/stable/getting-started/install-scylla/install-on-linux.html
scylladb : seeds ,rpc, listen addreess
sudo scylla_setup

create keyspace
cqlsh 

CREATE KEYSPACE IF NOT EXISTS employee_db
  WITH replication = {'class': 'SimpleStrategy', 'replication_factor': 1};
  
git clone https://github.com/OT-MICROSERVICES/salary-api.git

make build 
make fmt
make run-migrations
  
install migrate = curl -s https://packagecloud.io/install/repositories/golang-migrate/migrate/script.deb.sh | sudo bash
sudo apt install migrate

  
##################
 sudo apt install jq
 sudo apt install golang
  
 git clone https://github.com/OT-MICROSERVICES/employee-api.git
 
 change config.yaml ,migration.json
 

 
 http://3.79.243.190:8080/swagger/doc.json
 
 #################

 
 sudo apt install python3-poetry