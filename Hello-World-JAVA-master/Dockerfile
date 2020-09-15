FROM java:8
EXPOSE 6000
ADD http://192.168.43.121:8082/artifactory/libs-snapshot-local/com/nagarro/devops-tools/devops/demosampleapplication/1.0.0-SNAPSHOT/demosampleapplication-1.0.0-20200915.120227-1.war customermicroservice.war
ENTRYPOINT ["java","-jar" ,"customermicroservice.war"]