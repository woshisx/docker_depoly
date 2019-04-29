FROM centos
EXPOSE 80
CMD rpm -Uvh http://nginx.org/packages/centos/7/noarch/RPMS/nginx-release-centos-7-0.el7.ngx.noarch.rpm
CMD yum install -y nginx
CMD systemctl start nginx.service
CMD systemctl enable nginx.service
CMD nginx -g "daemon off;"