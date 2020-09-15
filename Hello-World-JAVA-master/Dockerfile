FROM java:8
EXPOSE 6000
ADD /target/devopssampleapplication.war devops.war
ENTRYPOINT ["java","-jar" ,"devops.war"]