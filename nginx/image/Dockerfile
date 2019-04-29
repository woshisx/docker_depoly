FROM centos
EXPOSE 80
CMD rpm -Uvh http://nginx.org/packages/centos/7/noarch/RPMS/nginx-release-centos-7-0.el7.ngx.noarch.rpm && yum install -y nginx && systemctl start nginx.service && nginx -g "daemon off;"