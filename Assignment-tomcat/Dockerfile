FROM centos:centos7

                #base image

RUN yum -y update 

                #checking for updates

                   
RUN yum install -y tomcat

                #install that package            

RUN yum clean all

                       
EXPOSE 8080


CMD ["catalina.sh","run"]  

#CMD ["./catalina.sh", "run"]

                     








