FROM centos
LABEL maintainer="Douglas Nunes <dglhenrique@gmail.com>" 

RUN yum -y install epel-release
RUN yum -y update
RUN yum -y install nginx
EXPOSE 80

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
