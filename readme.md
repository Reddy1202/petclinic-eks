This is java project

also builds using maven

it connects with the database(MySQL)

DB info pom.xml, schema.sql

we need to build : mvn clean package -P MySql

we are deploying to the eks(k8s)

code + Dockerfile








jenkins--- maven---
job : war file
/var/lib/jenkins/workspace/petclinic/target



pre-req: RDS

1) Create the RDS in the EKS VPC
public
private -- create the RDS in the private subnet

2) allow the RDS-SG of EKS worker node SG
3) allow the jenkins-sg to the rds-sg



