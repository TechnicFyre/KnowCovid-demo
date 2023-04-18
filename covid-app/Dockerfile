FROM mizzouceri/tomcat-mvn-java11:V1
MAINTAINER Songjie Wang "wangso@missouri.edu"

RUN yum update && yum install redhat-lsb-core  && yum install -y net-tools nano
RUN yum install -y default-mysql-server maven
WORKDIR /root 
ADD Covid19-website /root/Covid19-website
WORKDIR /root/Covid19-website
#RUN mvn clean package
#RUN cp /root/Covid19-website/target/*.war /usr/local/tomcat/webapp/Covid-19.war

