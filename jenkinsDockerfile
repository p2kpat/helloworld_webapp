FROM tomcat:latest
RUN apt-get update
RUN apt-get install -y net-tools
RUN apt-get install -y tree
COPY /var/lib/jenkins/workspace/ansible_playbook_project_test/target/demo.war /usr/local/tomcat/webapps/demo.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
