FROM centos
EXPOSE 80
RUN rpm -Uvh http://nginx.org/packages/centos/7/noarch/RPMS/nginx-release-centos-7-0.el7.ngx.noarch.rpm
RUN yum install -y nginx
RUN systemctl start nginx.service && systemctl enable nginx.service
ENTRYPOINT nginx -g "daemon off;"