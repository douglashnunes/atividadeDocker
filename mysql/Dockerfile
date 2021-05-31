FROM centos
LABEL maintainer="Douglas Nunes <dglhenrique@gmail.com>"

RUN yum -y install epel-release
RUN yum -y update
RUN yum -y install mysql-server

ENTRYPOINT [ "/bin/bash", "-l", "-c" ]
